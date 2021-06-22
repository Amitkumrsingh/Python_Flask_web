# Python_Flask
This Repository is created solely for learning!

# Getting started with flask
Use Window Powershell to created virtual env

Using following commands

     -pip install virtualenv

     -virtualenv env


### Activate Virtual Env 

       .\env\Scripts\activate.ps1

###  Now, you can install packages in virtual env
 let's install flask!

    -pip install flask


### Let's create flask minimal app

Create a file app.py (flask documentation recommendation)

    from flask import Flask
    app = Flask(__name__)

     @app.route('/')
     def hello_world():
        return 'Hello, World!'
     
     if __name__ =="__main__":
        app.run(debug=True)
        
### Run flask app

    python app.py

Congratulations! 🎉 

Your First flask app is available on

`localhost:5000`