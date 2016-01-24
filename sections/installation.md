## Installing the Symfony

--

### Symfony installer

1. Get a Symfony installer
```bash
$ sudo curl -LsS https://symfony.com/installer -o /usr/local/bin/symfony
$ sudo chmod a+x /usr/local/bin/symfony
```

2. Install
```bash
$ symfony new my_project 2.8
```

--

### Composer

1. Install composer (why don't you have it already? ^^)
```bash
$ curl -sS https://getcomposer.org/installer | php
$ sudo mv composer.phar /usr/local/bin/composer
```

2. Create Symfony Project
```bash
$ composer create-project symfony/framework-standard-edition my_project_name "2.8.*"
```

--

### RUN, Symfony, RUN

```bash
$ cd my_project/
$ php bin/console server:run
```

http://localhost:8000/