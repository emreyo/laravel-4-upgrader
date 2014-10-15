laravel-4-upgrader
==================

upgrades the project from laravel 4.1 to 4.2 - bash

**usage:**

**go to your project root and execute lupgrader** - as in LaravelUPGRADER. yeah, that's an L. 

you can either run like this: 

    bash lupgrader

or: 

    chmod +x lupgrader
    ./lupgrader

have fun

for more information, you can visit [Upgrade Guide](http://laravel.com/docs/4.2/upgrade) section of [Laravel Documentation](http://laravel.com/docs)

this script simply updates your User model and database. 

* first, it gets the path and name of User model in case you changed them. (set in script)

* checks for appropriate functions' existence in your model. updates if necessary. 

* creates a backup of your database (mysqldump) and then updates according to documentation. 

written because of boredom... I guess nobody is using 4.1 now, but I hope I can help someone, somehow. either by upgrading their framework to 4.2, or by my silly shell script :/
