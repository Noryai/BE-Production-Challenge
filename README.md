# Back End Production Challenge

<p align="center">
    <img alt="Nory Logo"
        src="https://nory.ai/static/media/n-logo.34190c70.svg"
    />
</p>

Congratulations for making it to the challenge stage of the interview process 💪! 

This BE Production Challenge allows you to demonstrate your skills in Back end and Devops tasks and emulate the work that we do here at Nory; 

It will likely take 3-4 hours total, but if you find it's taking longer than that, just wrap up what you have and finish off with some pseudo-code to explain what you would do next. Seeing how you prioritize under time restrictions is really useful too.

After you complete this challenge we will have a meeting where you will present and discuss this project, see more details in the [What We'll Talk about in the Call Section](#what-well-talk-about-in-the-call).


 
## Overview
 
 Your team was tasked with creating a backend for CRUD operations of some resources. They have come up with the models and a basic Flask app to manage it. However, the app is far from ready for production. 


### Technical Requisite
As a production champion you have decided to take on the challenge and do the following

1.  **Must** - Replace the sqlite db with a production grade db of your choice.
2.  **Must** - Add an e-2-e test for the delete method *only* (let other team members follow your lead and implement the rest).
3.  **Must** - Package the app using Docker.
4.  **Must** - Use a CI/CD pipeline (on git hub/lab/bucket etc.) to run the tests on each commit.
5.  **Should have** - Proper use of git and a professionally managed project (commit early and commit often).
6.  **Should have** - Proper documentation that explains how to setup the app and run the tests.


## Resources

You are given this very basic CRUD flask web app, using sqlite as DB with an entries model.

(forked from [this repo](https://github.com/gurkanakdeniz/example-flask-crud))

Please create your own git repository for this exercise.

  
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

## What We'll Talk About in the Call

Once you've completed the challenge let us know and will set up a call where we can talk through it. 

We'll ask questions about what approach you took and why. We'll ask questions about what assumptions you might have made, and why.

From there we will also look at the code and hear any decisions that you have made.  

And of course, we want to hear your thoughts and answer any questions you have.


## tl;dr

So that's that. How does it sound? A whole lot of details, we know !!!

**Oh, and one last thing... best of luck! We're really happy you've decided to take part in the challenge, and we look forward to seeing your epic solution.** 😎


_Disclaimer: upon accepting your code, Hospitality Growth Limited, t/a Nory, you give us permission to delete the work once the interview process has been completed. You agree that this is in accordance with EU GDPR legislation._
