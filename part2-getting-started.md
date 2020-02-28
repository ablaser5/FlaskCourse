# Flask Web Development Course

In this course, we will be learning python web development using flask. We will build
a complete online store from scratch, covering front-end development, back-end development,
database interaction, and security in flask.

Requirements: A machine running Mac Os or Linux. Windows users should look into virtual machines
or installing a linux subsystem. 

### Getting Started with Flask

1. Environment Setup
	* File and Directory Structure
	```
	mkdir templates
	```
	```
	mkdir static
	```
1. Starting the Project
	* Create a file called 'main.py'
	* Open the file with your editor or IDE and paste in this snippet:
	```python
	from flask import Flask

	app = Flask(__name__)

	@app.route("/")
	def home():
	    return "Hello, World!"
	    
	if __name__ == "__main__":
	    app.run(debug=True)
	```
1. Running the App
	```
	python3 main.py
	```
	* This will run the application on your localhost (http://127.0.0.1:5000/)
	
![alt text](https://github.com/ablaser5/FlaskCourse/blob/master/materials/running_the_app.png "Logo Title Text 1")
