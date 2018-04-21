## Introduction

add PostMark driver to laravel Mail facades

## Installation

```
composer require cammac/postmark
```

### Service Provider

if your Laravel below 5.5 you need to add PostMarkServiceProvider

in `config/app.php` in `providers` list 
```
\Cammac\Postmark\PostMarkServiceProvider::class,
```

### Configuration

In .env file change MAIL_DRIVER to "postmark"

```
MAIL_DRIVER=postmark
POSTMARK_SECRET=your-api-token
```

## License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).