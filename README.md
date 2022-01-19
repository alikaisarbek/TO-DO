# To-Do assignment1
## Title
build a ToDo application with authentication using Django Web Framework 






## Installation

```bash
pip install django
pip install psycopg2
pip3 install mysql
python manage.py runserver
```
## Usage
```bash
Here we start our server 
Then go to server  http://127.0.0.1:8000/
```
## Example
```bash
from django.shortcuts import render,redirect
from django.views.generic.list import ListView
from django.views.generic.edit import CreateView, UpdateView, DeleteView, FormView
from django.urls import reverse_lazy
from .models import ToDo
from django.contrib.auth.views import LoginView, LogoutView
from django.contrib.auth.mixins import LoginRequiredMixin
from django.contrib.auth.forms import UserCreationForm
from django.contrib.auth import login 
```
```bash
