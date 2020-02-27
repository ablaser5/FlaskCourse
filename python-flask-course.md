# Flask Web Development Course

In this course, we will be learning python web development using flask. We will build
a complete online store from scratch, covering front-end development, back-end development,
database interaction, and security in flask.

Requirements: A machine running Mac Os or Linux. Windows users should look into virtual machines
or installing a linux subsystem. 

### Introduction
1. Introduction to the Command line
	1. Start by opening up a terminal. This is called "Terminal" on the Mac. On Linux this will be
	called the Console or Command Line.
	1. Next, type the following commands into the Command Line:
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
	1. Check if you already have python 3 installed
	```
	python3 --version
	```
	```
	python --version
	```
	###### * If Either of these commands give a python version 3.6.1 or higher you will be set
	1. Using the Command Line Enter the Following Commands:
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
	1. After Python is installed, create a virtual environment:
	```
	python3 -m venv venv
	```
	1. Activate the virtual environment by typing:
	```
	source venv/bin/activate
	```
1. Installing flask
	1. With the virtual environment activated, type:
	```
	pip3 install flask
	```
1. Installing MySQL and Configuration
	##### Mac
	```
	brew install mysql
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

1. Starting a Flask Project
	1. Environment Setup
	1. Connecting to the Database
 
