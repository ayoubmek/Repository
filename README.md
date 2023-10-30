# Repository
Repository

//create a new database for your Symfony application.

php bin/console doctrine:database:create


//generate a new migration file for your Symfony application.

php bin/console make:migration

//execute all of the pending migrations in the migrations/ directory.

php bin/console doctrine:migrations:migrate


//run your Symfony application during development.

symfony serve
