# DataTables Editor Plugin

This package is a plugin of [Laravel DataTables](https://github.com/yajra/laravel-datatables) for processing [DataTables Editor](https://editor.datatables.net/) library.

> {tip} Special thanks to [@bellwood](https://github.com/bellwood) and [@DataTables](https://github.com/datatables) for being [generous](https://github.com/yajra/laravel-datatables/issues/1548) for providing a license to support the development of this package.

A [premium license](https://editor.datatables.net/purchase/index) is required to be able to use [DataTables Editor](https://editor.datatables.net/) library.

<a name="installation"></a>
## Installation

Run the following command in your project to get the latest version of the plugin:

```bash
composer require yajra/laravel-datatables-editor:"^12.0"
```

<a name="configuration"></a>
## Configuration

> This step is optional if you are using Laravel 5.5

Open the file ```config/app.php``` and then add the following service provider.

```php
'providers' => [
    // ...
    Yajra\DataTables\EditorServiceProvider::class,
],
```

And that's it! Start building out some awesome DataTables Editor!
