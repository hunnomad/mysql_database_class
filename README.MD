## MySQL Database connection skelton

If you want to use the .env enviroment, please run:

...
composer require vlucas/phpdotenv
...

If you installed the .env environment, please insert into the necessary .php file the following lines:

...
$dotenv = Dotenv\Dotenv::createImmutable(__DIR__);
$dotenv->safeLoad();
...

**Never forget. _DO NOT push the .env file_ to the github repo, put it as an exception in the .gitignore file.**