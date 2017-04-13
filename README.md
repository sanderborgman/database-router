Vegas CMF Database router
======================

INSTALL/RUN OLD-SCHOOL
--
```
cp ./tests/config.php.sample ./tests/config.php
composer install
php ./vendor/bin/phpunit -c tests/phpunit.xml
```

INSTALL/RUN DOCKER
--
```
cp ./tests/config.php.sample ./tests/config.php
yake composer install
yake up
yake phpunit -c tests/phpunit.xml
```