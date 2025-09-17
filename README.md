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

If everything works, you could somewhere in one of your PHP files do:

```php
print_hello_world();
```
