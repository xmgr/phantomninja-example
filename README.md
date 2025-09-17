# Sample repository

## What to do

On your machine, go to some directory (e.g. `/var/www` or something) and clone this repository. So, open terminal and type:

```
git clone git@github.com:xmgr/phantomninja-example.git
```

You now have a folder like `/var/www/phantomninja-example` with the code from `main` branch checked out.

Then, navigate into your project's folder (whatever project you have laying around somewhere) and in some file add:

```php
require_once '/var/www/phantomninja-example/bootstrap.php';
```

If everything works, you could in your project now call:

```php
print_hello_world();
```

You could (in terminal) now navigate into `/var/www/phantomninja-example` and run

```shell
git checkout --track origin/develop
```

This would "check out" the `develop` branch. Meaning, when again running `print_hello_world()`, you would see the message "Hello World in develop branch :)".

If the `develop` branch already exists, you could also run:

```shell
# Select the branch:
git checkout develop
# Pull the newest changes from Github:
git pull
```
