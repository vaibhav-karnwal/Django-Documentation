# Django Documentation

## Environment Creation

### advantage:
* By creating virtual enviroment there will not be any effect in your laptop enviroment.
* What packages you will install in virtual enviroment that will not be effect outside enviroment. 

### Procedure

* You have to make a folder like (projects)
* that folder will be your virtual enviroment
* write cmd "pip install virtualenv"
* you can chack the verion by cmd "virtualenv --version" of your virtualenv
* now create your virtual enviroment in that folder by cmd "virtualenv pyenv" (pyenv is the name of the virtual enviroment)
* To activate virtual enviroment write cmd "pyenv\Scripts\activate"
* If there is any error occouring then you have to change execution policy then wite cmd
       "set-executionpolicy remotesigned" to change execution policy.
* Now you can again write cmd "pyenv\Scripts\activage"  your virtual enviroment will be created
* To deactivate this enviroment then write cmd "deactivate"
* If you want to install django version 2.2
        then write command "pip install django==2.2"

### NOTE: 

If you wona send you poject to your partnet then you no need to give him you full folder
      for it you have to make a requirement file for your virtual enviroment
      (1): First activate this VEnviroment 
      (2): And write command "pip freeze > requirements.txt"
      (3): Your requiremts.txt file will be created in the folder
      (4): There will be all the information of the packages which you install for that enviroment



### (One More Thing): 
If you wona make a enviroment which can access all the packages of your laptop enviroment
              then write cmd "virtualenv --system-site-packages myenv" (myenv is the name of the enviroment) 
              
              
### why django is used
* django is a frame work of python programming which is used to make web application it makes easy to create website 


### If you wona install django in vertual enviroment 

* step(1): go to in your virtual enviroment
* step(2): write cmd "pip install django==(django version name)"
* step(3): By cmd "django-admin --version" you can chack it is installed or not

### For creating first project

* step(1):go to in your virtual enviroment
* step(2):write cmd "django-admin startproject (project name like first_project)" 
* step(3):go inside your first_project by cmd in this project you will get a manage.py file by this file
        you can run your server with command "python manage.py runserver" you will get a link and paste this 
        link into the chrome.
* step(4):open your project in any IDE(Intigrated Development Enviroment) like VScode
* step(5):To create your app(it is a combination of web pages)
* step(6):you have to write cmd "python manage.py startapp (AppName like first_app)"
* step(7):there will be multile files in your app but there will not be urls
        file so first you have to make ulrs file in your app
* step(8):after making urls file you have to import path in urls file
        "from django.urls import path" 
* step(9):if you wona went to another page from one page so you have to 
        import views(it will provide a facilty to go one page to another page)
        "from . import views"
* step(10):you have to make a list of ulrpatterns in urls file
         "urlpatterns=[path('',views.home,name="home")]"
         (views.home=it will call home function in your app's views file)
         (name=it is the name of the page)
* step(11):you have to make and home function in to the views file 
         open app's views file and make home function
        "def home(request):
               return HttpResponse("Hellow This Is Shagun")
        "
        this function will return HttpResponse() function and whatever you will
        pass the string will show into your home page
        
Note: you have to import a package in your views file "from django.http import HttpResponse"

* step(12):your app will be created 
* step(13):you have to link your app with your project
           (1):open your project's urls file
           (2):make a path in urlpatterns
           (3):"path('',include('first_app.urls')),"
           (4):you have to import include "from django.urls import include"
* step(14): now you can run your server with terminal "python manage.py runserver"
          copy the link and paste in your chrome              
          
          
</li><li>•	Widgets - Widgets are the building blocks of flutter applications. Widgets describe what their view should look like which is completely depends upon the choice and sequence of the widgets used to build the app.
</li><li>•	Structure of the code of an app is a tree of widgets.
</li><li>•	Scaffold – Implements the basic material design visual layout structure.
</li><li>•	AppBar – To create a bar at the top of the screen.
</li><li>•	Text  To write anything on the screen.
</li><li>•	Container – To contain any widget.
</li><li>•	Center – To provide center alignment to other widgets.
</li><li>•	Container Class -  Container class can be used to store one or more widgets and position it on the screen according to our convenience. 
</li><li>•	child:  Container widget has a property ‘child:’ which stores its children. The child class can be any widget. Example - taking a text widget as a child. 
</li>
