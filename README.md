# sample-ansible-project
## Introduction
This is a sample project of ansible. I have collected the flask app from below link
https://github.com/mmumshad/simple-webapp
and I am following mmumshad's advanced ansible course.

## First Project

Run below command to up a python app. This python_app.yaml file will first install some dependencies, install mysql db and create a database
and run the flask app.

'ansible-playbook python_app.yml -i inventory.txt'


To run the jobs with ansible roles use below command

ansible-playbook python_app_with_role.yaml -i inventory.txt