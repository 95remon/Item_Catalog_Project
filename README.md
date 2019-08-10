Project Title:

Item Catalog  - v0.1 :-
Create a restaurant menu app where users can add, edit, and delete restaurants and menu items in the restaurants.



Skills used for this project :

Python
HTML
CSS
Bootstrap
Flask
SQLAchemy
OAuth2
Google Login



installing and running :

step #1 : download and install Oracle virtulebox
    (link:https://www.virtualbox.org/wiki/Downloads)
    
step #2 : download and install vagrant
    (link:https://www.vagrantup.com/downloads.html)
    
step #3 :  clone the udacity-fullstack-vm vagrant file in order to run the project
    (link:https://github.com/udacity/fullstack-nanodegree-vm)
    
step #4 : Unzip and place the Item Catalog project folder in your Vagrant directory

step #5 : open your git Bash and cd the Item Catalog file path and run (vagrant up) it takes time and then run (Vagrant ssh)

step #6 : Now cd vagrant file run (cd /vagrant)

step #7 : run (python database_setup.py) to setup your database 

step #8 : run (python lotsofmenus.py) to add records 

step #9 : And now run (Python project.py)

step #10 : open your favourite browser and use this link (http//:localhost:5000) 



Main Functions:

1-JSON Endpoints:-

JSON APIs to view Restaurant Information:
(/restaurant/<int:restaurant_id>/menu/JSON)
(/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON)
('/restaurant/JSON')

2-CRUD for categories and Items : Create , Update , delete (on login)

3-Authentication and Authorization

4-Google signin



Authors: 
    Remon Louis