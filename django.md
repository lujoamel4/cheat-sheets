# Everydays tasks

## Migrations
### After modify models
- python3 manage.py makemigration
- python3 manage.py migrate

## Store and restore database
- __fixture__ folder is convention in Django to dump and restore database

### dump database (Store)
- ''' python3 manage.py dumpdata {app}.{model} --format=json --indent=4 >{appFolder}/fixtures/{targetFileName}.json '''


- example: ''' python3 manage.py dumpdata products.Product --format=json --indent=4 > products/fixtures/products.json '''

### load data (Restore)
    ''' python3 manage.py loaddata {filename} '''
- __fileaname__ should be inside __fixture__ folder
