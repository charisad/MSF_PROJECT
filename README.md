# Django Rest Project MFS AFRICA
A project to show how two services(APIs) communicate with each other.

The Home project is used to demonstrate how to use the two APIs in a single web page.

### Running the project...


### The Quotes project
   Cd into Quotes
   
   Run python manage.py makemigrations
   
   Run python manage.py migrate
   
   Run python manage.py createsuperuser
   
   Run python consumer.py
   
  
### The Likes project

   Cd into Likes
   
   Run python manage.py makemigrations
   
   Run python manage.py migrate
   
   Run python manage.py createsuperuser.Create a superuser similar to the one above. 
   
   Run python consumer.py
   
### Communication
  Make sure you have RabbitMQ and pika installed.
  
  Start the server by running `sudo service rabbitmq-server start` if on linux
  
  There are also instructions for [Windows](https://www.rabbitmq.com/install-windows-manual.html) and [Mac](https://www.rabbitmq.com/install-homebrew.html) users.
  
  Create edit or delete quotes on Quotes project and similar opertaions happen at the Likes project.
  
  
   
 ### The Home project

   Run python manage.py makemigrations
   
   Run python manage.py migrate
     
   Run python manage.py runserver

