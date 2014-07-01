#Example

```php
<?php

require 'AllPositions.php';

$api = new AllPositions('api_key_value');

var_dump(
  $api->get_project(12345)
);

```
