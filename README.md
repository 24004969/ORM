# Ex02 Django ORM Web Application
# Date:
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM
## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM

    from django.db import models                                                                                                                                                                                          
    from django.contrib import admin                                                                                                                                                                                      
    class footballplayer (models.Model):                                                                                                                                                                                

    name=models.CharField(max_length=20)                                                                                                                                                                              
    weight=models.IntegerField()                                                                                                                                                                                      
    players_id=models.CharField(max_length=100)                                                                                                                                                                       
    age=models.IntegerField()                                                                                                                                                                                         
    members=models.CharField(max_length=20)

    class footballplayerAdmin(admin.ModelAdmin):                                                                                                                                                                         

    list_display=('name','players_id','weight','age','members')

    admin.py

    from django.contrib import admin                                                                                                                                                                                         
    from django.contrib import admin                                                                                                                                                                                                   
    admin.site.register(footballplayer,footballplayerAdmin)

# OUTPUT

![image](https://github.com/user-attachments/assets/984c27cc-1439-4852-ba1e-1e02d127667a)


# RESULT
Thus the program for creating a database using ORM hass been executed successfully
