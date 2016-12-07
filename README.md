
Flynn WP
========

A template for installing and running WordPress on Flynn.


Installation
------------

1. Clone this git repo `$ git clone https://github.com/zomnium/flynn-wp.git wordpress`
2. Get into the new directory `$ cd wordpress`
3. Create a Flynn application `$ flynn create wordpress`
4. Add a database to the application `$ flynn resource add mysql`
5. Push to deployment `$ git push flynn master`

You can replace 'wordpress with your own application name (lowercase and no spaces or special charactars).

**Important note:** please change the authentication keys and salts in public/wp-config.php! Using default values will be a security risk in production.


Usage
-----

Always commit changes into git and you can use `$ git push flynn master` to push it into production.


Resources
---------

More about working with Flynn, [read the docs](https://flynn.io/docs).


To do
-----

- [ ] File storage 
- [ ] Improve default configuration 
