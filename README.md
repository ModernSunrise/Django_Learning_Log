# Django_Learning_Log
My First Django Project "Learning Log"
I built this project with the help of 'Python Crash Course by Eric Matthes' to learn Pythons Django web framework.

Tools used: 
Python 3.10.4,
Bootstrap 4.0.4,
SQLite 3.38

Learning Log is a blog site that users can register an account on, Log in, and create Topics about what they have learned.
In those topics you can write entries which will then be saved to the topic and timestamped.

This project was later pushed to an Elastic Beanstalk enviroment to make it public for a short time before taken down.

My main takeaways from this project code wise were the relationships between urls.py, views.py, and templates, which live at the heart of every Django project.

My largest struggles actually appeared when it was time to deploy this webapp to Elastic Beanstalk. I learned the hard way that Elastic Beanstalk can only host up
to python 3.8.5. 
This fact had me learn the usefullness of the module pyenv to install legacy python versions and utilize them in my project. If anyone reading this needs help,
this URL: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-django.html is infitely helpful.
