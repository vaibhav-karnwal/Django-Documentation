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
