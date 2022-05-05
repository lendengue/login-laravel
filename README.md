## Sistema de Login Laravel com Breeze

##### Iniciar projeto
composer create-project laravel/laravel sistema-login-laravel --prefer-dist

##### Vincular com seu repositório no git
git init
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/{seu-user}/{seu-repositorio.git}
git push -u origin master

##### Colocando o Breeze no projeto

composer require laravel/breeze -dev
php artisan breeze:install
npm install (Necessário [NodeJS](https://nodejs.org/en/))
npm run dev
