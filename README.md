# minerva-web-token-api
API para consumir recursos do servidor minerva-web-token-server

Cria um token e envia para o celular da pessoa.

```php
$webTokenApi = new Minerva\WebToken\Api\Client([
  'namespace' => '...',
  'token'     => '...'
]);

$webTokenApi->createFor('phoneNumber'); // return true/false
```

```php
$webTokenApi = new Minerva\WebToken\Api\Client([
  'namespace' => '...',
  'token'     => '...'
]);

$webTokenApi->isValid('token'); // return true/false
```
