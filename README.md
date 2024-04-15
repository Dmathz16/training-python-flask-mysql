# Flask MySQL

This simple flask application is from this [documentation](https://flask.palletsprojects.com/en/3.0.x/tutorial/) that I've converted from [using sqlite database](https://github.com/Dmathz16/training-python-flask-sqlite) to mysql (this).

## Requirements
Windows:
* [python](https://www.python.org/downloads/)
* mysql from [xampp](https://www.apachefriends.org/), [wamp](https://www.wampserver.com/en/) or other sources that you know.

## How to run?
1. Make sure the requirements are installed and running.
2. Clone/download then extract this project.
3. Open cmd/terminal then cd to this project.
   >>> cd PATH_OF_THE_PROJECT
4. Generate virtual environment:
   >>> py -3 -m venv .venv
5. Activate environment:
   >>> .venv\Scripts\activate
6. Install modules:
   >>> pip install -r requirements.txt 
8. Generate mysql database:
   >>> python application/db.py
9. Run project:
   >>> flask --app application run --debug

## Output
![image](https://github.com/Dmathz16/training-python-flask-sqlite/assets/54519505/ef771fda-0d00-4d6b-98b1-fc7343d75172)
