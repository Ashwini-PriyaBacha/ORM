# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```python
from django.db import models

# Create your models here.
class Student(models.Model):
    user=models.CharField(max_length=100)
    password=models.CharField(max_length=100)
    email=models.EmailField()
    phone=models.CharField(max_length=100)
    profile=models.ImageField(upload_to='profile/')
    address=models.TextField()
```


## OUTPUT
![Screenshot 2025-03-19 162239](https://github.com/user-attachments/assets/0c80c919-3f3e-4e22-a5e9-637e214c7784)

Include the screenshot of your admin page.


## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
