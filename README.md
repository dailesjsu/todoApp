### todoApp
It is a basic todo App


## Idea: It is a basic todo Web App, which allows user to add todo tasks and delete them. 


## Requirement: 
Python, Django, HTML


# How to run it: 


# Dowload the code and run on terminal: 
      pipenv shell
      python manage.py runserver
      weblink: http://127.0.0.1:8000/todo/
      
      
# Run database: 
      python manage.py shell
      from todo.models import TodoItem
      TodoItem
      TodoItem.object.all()
      all_todo_items = TodoItem.objects.all()
