ToDoList
========

Base du projet #8 : Améliorez un projet existant

https://openclassrooms.com/projects/ameliorer-un-projet-existant-1

## Installation
Clonez le repo :
git clone https://github.com/damienvalade/OC-P8-TODOLIST.git
Modifier le .env avec vos informations.

### Installez les dependances :
- `composer install`

### Mettre en place la BDD :
- `php bin/console doctrine:database:create`
- `php bin/console doctrine:migrations:migrate`