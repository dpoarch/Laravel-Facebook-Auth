# Requirements
- Laravel 5.8^ or greater
- Composer
- Php 7.1^


# Installation

open your command line and run

```
  
  composer install

```


create a database named 

```

	social 

```
in your phpmyadmin

and open .env file

```php

	DB_HOST=127.0.0.1
	DB_DATABASE=social
	DB_USERNAME=root
	DB_PASSWORD=

```

run on your cli

```

   php artisan migrate

```

also run on your cli

```

	php artisan db:seed

```


port starts with localhost:8000


Your good to go!