# Yii

Example [Yii](https://www.yiiframework.com/) app. Yii is a fast, secure PHP framework for building web applications.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `8000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
composer install

# run in development mode
YII_DEBUG=1 YII_ENV=dev php yii serve
```

The app opens at `http://localhost:8080`. Requires PHP 8.5 with the GD extension.
