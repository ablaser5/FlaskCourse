# Flask Web Development Course

In this course, we will be learning python web development using flask. We will build
a complete online store from scratch, covering front-end development, back-end development,
database interaction, and security in flask.

Requirements: A machine running Mac Os or Linux. Windows users should look into virtual machines
or installing a linux subsystem. 

### Introduction

1. Introduction to the Command line
	* Start by opening up a terminal. This is called "Terminal" on the Mac. On Linux this will be
	called the Console or Command Line.
	* Next, type the following commands into the Command Line:

	```
	cd
	```
	```
	mkdir FlaskApp
	```
	```
	cd FlaskApp
	```
1. Virtual Environment Overview
	* Check if you already have python 3 installed

	```
	python3 --version
	```
	```
	python --version
	```
	###### If Either of these commands give a python version 3.6.1 or higher you will be set
	* Using the Command Line Enter the Following Commands:
		##### Mac
		```
		brew install pyenv
		```
		```
		pyenv install 3.6.1
		```
		##### Linux (Debian)
		```
		sudo apt-get update
		```
		```
		sudo apt-get install python3.6
		```
	* After Python is installed, create a virtual environment:

	```
	python3 -m venv venv
	```
	* Activate the virtual environment by typing:

	```
	source venv/bin/activate
	```
1. Installing flask
	* With the virtual environment activated, type:

	```
	pip3 install flask
	```
1. Installing MySQL and Configuration
	##### Mac
	```
	brew install mysql
	```
	* Set the root user's password for MySQL here
	```
	mysql -u root password 'Enter Your Password Here'
	```
	##### Linux (Debian)
	```
	sudo apt update
	```
	```
	sudo apt install mysql-server
	```
	```
	sudo mysql_secure_installation
	```
	* Now, you should be able to access MySQL using the command:
	```
	mysql -u root -p
	```
 
