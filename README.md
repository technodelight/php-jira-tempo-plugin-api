# php-jira-tempo-plugin-api
PHP API layer for Tempo TimeSheets

## usage

```php
<?php

use Technodelight\Tempo2\HttpClient;
use Technodelight\Tempo2\Api;

$apiToken = 'your api token here, can be obtained in your jira instance';
$api = new Api(new HttpClient($apiToken));
var_dump($api->all()); // for test
```

## requirements

You need an API token for communicating with tempo REST APIs
Documentation could be found here https://tempo.io/doc/timesheets/api/rest/latest/