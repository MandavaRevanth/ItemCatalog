
# item-catalog
>Log analysis is the part of [UDACITY-FULL-STACK-NANO-DEGREE](https://in.udacity.com/course/full-stack-web-developer-nanodegree--nd004)


### Abstract
******************************************************************************************************
> This Project is a RESTful web application utilizing the Flask Framework which accesses a SQL database that populates cricket country categories and their cricket players information. OAuth2 provides authentication for furuther CRUD functionality on the application. Currently OAunt2 is implemented for Google Accounts.

### I have 3 python files
******************************************************************************************************
> This project has one main python module `bike.py` which runs the flask application. A SQL database is created using the `showroom_database.py` module and you can populate the database with test data using `showroom_info.py`

The Flask application uses stored HTML templates in the templates directory to build the front-end of application.


### Software Requirements
------------------------------------------------------------------------------------------------------
* Python3 -------------------->[https://www.python.org/downloads/]

* VirtualBox ----------------->[https://www.virtualbox.org/wiki/Downloads]

* Vagrant -------------------->[https://www.vagrantup.com/downloads.html]

* Git ------------------------>[https://git-scm.com/downloads]

* SQLite DB ------------------>[https://sqlitebrowser.org/dl/]

* Text Editor(Sublime Text3)-->[https://www.sublimetext.com/3]
 


### Required Skills for item catalog
------------------------------------------------------------------------------------------------------
* Python3
* HTML
* CSS
* Bootstrap
* OAuth
* Flask Framework
* sqlalchemy

## How to run the Project
----------------------------------------------------------------------------------------------------------

 * Go to `vagrant` folder and run `cmd` or `gitbash.`

###### Launch the vagrant.
---------------------------------------------------------------------------------------------------------- 

```sh

vagrant up

vagrant ssh

cd /vagrant

```

### How to run python files
-------------------------------------------------------------------------------------------------------
* `python showroom_database.py`
* `python showroom_info.py`
* `python bike.py`

### Install libraries
------------------------------------------------------------------------------------------------------
* pip install Flask
* pip install sqlalchemy
* pip install requests
* pip install psycopg2
* pip install oauth2client

### Google Authentication
------------------------------------------------------------------------------------------------------
 -  Go to any browser open [console.developers.google.com](https://console.developers.google.com)
 -  Create a new project based on your project.
 -  Then click on `Credentials` for create a new credentials.
 -  There will be on dropdown box.
 -  Click on OAuth clent ID.
 -  Then you will see a option format for application type.
 -  Select on `WEB_APPLICATION`, and click on create button.
 -  Fill the Columns with appropriate http url's.
 -  Download the `JSON` file.
 -  Rename `JSON` file into `clent_secrets.json`.
 -  Place the `JSON` file in item-catalog file.

### JSON Endpoints
*********************************************************************************************************
The following are open to the public:

Showroom Catalog JSON: localhost:5000/country/JSON'

- It displays the whole showroom catalog. Showroom categories and all players.
Bikewise JSON: localhost:5000/showroom/<int:bike_id>/menu/JSON

- Based on player id it  will displays the particular showroom bike.
showroom of particular bike details JSON: localhost:5000/showroom/<int:showroom_id>/menu/<int:bike_id>/JSON

- it displays the particular showroom of particulr bike information.


-----------------------------------------------------------------------------------------------------------
<p align="right">
	By -> Mandava Revanth
</p>

