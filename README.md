flaskgur
========

Simple image hosting site written with Flask and Python

Screenshot
----------
![alt text](http://i.imgur.com/QBmadgE.png "Uploaded image")
![alt text](http://i.imgur.com/rmqTSx1.png "Tile view")

www.chokepoint.net

How to deploy
----------

~~~
$ sudo pip install virtualenv
$ git clone https://github.com/kawa-/flaskgur
$ cd flaskgur
$ virtualenv venv
$ . venv/bin/activate
$ pip install Flask pillow
$ sqlite3 flaskgur.db < schema.sql
$ ./run.sh
~~~

