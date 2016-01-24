## Concept of an Environment

- Development
- Production
- CLI
- Tests / Stage 

--

### Staging env example

- Create staging config: app/config/config_staging.yml

```yml
imports:
    - { resource: config.yml }

# Custom config
```

- Execute staging env: web/app_staging.php

```php
$kernel = new AppKernel('staging', false);
$kernel->loadClassCache();

$request = Request::createFromGlobals();
$response = $kernel->handle($request);
$response->send();
$kernel->terminate($request, $response);
```
or

```php
$ app/console -e staging
```
