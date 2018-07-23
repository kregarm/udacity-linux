# Server configuration

## Connecting to server
ip: 18.185.95.65
port: 2200
url: http://18.185.95.65

## Installed software

### Server

* apache2
* mod-wsgi
* git
* Postgresql
* Virutalenv

### App
* Flask
* Pip3
* Sqlalchemy
* Psycopg2
* oauth2client
* requests
* httplib2


## Modifications

### Auth
Switched the default port for SSH from 22 to 2200, disabled password login and enabled the UFW.

### Accounts
Added a new Grader account,granted them the sudo permissions and created the RSA key for SSH.

### Server
Configured timezone, installed required applications and packages and enabled the virtualenv. Created and configured the DB user 'catalog'.

## Resources
* [Harushimo's linux config github](https://github.com/harushimo/linux-server-configuration)
* [Flask deploy article from Leon Wang](http://leonwang.me/post/deploy-flask)


