Todo Web Application using Django REST framework, MySQL, and React.js<br>

This is a Todo Web Application developed using Django REST framework, MySQL, and React.js. This Platform can perform CRUD operation on individual data and will store the data in a MySQl database. This application has React.js in the frontend and Django in the backend and both are connected through API.<br>
React is a JavaScript framework for developing SPAs (single-page applications). It has solid documentation and a vibrant ecosystem around it.<br>
Django is a Python web framework that simplifies common practices in web development. Django is reliable and also has a vibrant ecosystem of stable libraries supporting common development needs.<br>
For this application, React serves as the frontend, or client-side framework, handling the user interface and getting and setting data via requests to the Django backend, which is an API built using the Django REST framework (DRF).<br>

HOW TO RUN <br>
•	git clone https://github.com/mdakram09/Todo-Web-Application-using-Django-REST-framework-MySQL-and-React.js.git<br>
•	pip install virtualenv<br>
•	virtualenv venv<br>
•	source activate venv<br>
•	pip install -r requirements.txt<br>
•	create a mysql database with name todo_data<br>
•	change your username and password for mysql data base in the backend/backend/settings.py file<br>
•	cd backend<br>
•	python manage.py migrate<br>
•	python manage.py runserver<br>
•	cd ..<br>
•	cd frontend<br>
•	npm install<br>
•	npm start<br>

