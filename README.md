# Back End Production Challenge

Congratulations for making it to the challenge stage of the interview process 💪! 

This BE Production Challenge allows you to demonstrate your skills in Back end and Devops tasks and emulate the work that we do here at Nory; 

It will likely take 1-2 hours total, but if you find it's taking longer than that, just wrap up what you have and finish off with some pseudo-code to explain what you would do next. Seeing how you prioritize under time restrictions is really useful too.

After you complete this challenge we will have a meeting where you will present and discuss your approach;


 
## Challenge Overview
 
 Your team was tasked with bringing this web app closer to production grade level; 
 As a production champion you have decided to take on the challenge and do the following: 
 - Replace the sqlite db with a production grade db of your choice
 - Add an e-2-e test for the delete method *only* (let other team members follow your lead and implement the rest)
 - Package the app using Docker
 - Use a CI/CD pipeline (on git hub/lab/bucket etc.) to run the tests on each commit; 

  Good luck ☘️ ️with your ticket ! 

## Resources

You are given this very basic CRUD flask web app, using sqlite as DB with an entries model.

(forked from [this repo](https://github.com/gurkanakdeniz/example-flask-crud))
  
### Installing Locally for Linux

```
git clone https://github.com/gurkanakdeniz/example-flask-crud.git

cd example-flask-crud/

python3 -m venv venv

source venv/bin/activate

pip install --upgrade pip

pip install -r requirements.txt

export FLASK_APP=crudapp.py

flask db init

flask db migrate -m "entries table"

flask db upgrade

flask run
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
