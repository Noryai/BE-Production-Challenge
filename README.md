# Back End Production Challenge

 Welcome to the BE Production Challenge 💪 !

 This is a very basic CRUD flask web app, using sqlite as DB and basic entries model.
 
 Thanks for gurkanakdeniz - It is forked from his repo [here](https://github.com/gurkanakdeniz/example-flask-crud)
 
# The Challenge
 
 your team was tasked with bringing this web app closer to production grade app; 
 As a production champion you have decided to take on the challenge and do the following: 
 - Replace the sqlite db with a production grade db of your choice
 - Add an e-2-e test for the delete method
 - Package the app using Docker
 - Use a CI/CD pipeline to run the tests on each commit; 

  Good luck ☘️ ️with your ticket ! 
 
### Installing (for linux)

open the terminal and follow the white rabbit.


```
git clone https://github.com/gurkanakdeniz/example-flask-crud.git
```
```
cd example-flask-crud/
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip install --upgrade pip
```
```
pip install -r requirements.txt
```
```
export FLASK_APP=crudapp.py
```
```
flask db init
```
```
flask db migrate -m "entries table"
```
```
flask db upgrade
```
```
flask run
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
