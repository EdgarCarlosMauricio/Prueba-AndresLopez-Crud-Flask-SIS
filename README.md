## INSTRUCCIONES QUE FALTARON
Instalar Dependencias Directamente ya que esta en python 3.9 y ya todo esta un .10 o .11 y devolverse es complicado
pip3 install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy flask-httpauthflask-httpauth werkzeug

python3 ./app.py

http://127.0.0.1:5000/
Pide auth
Son login:andy pass:password
o test pass: pwd

http://127.0.0.1:5000/create/
http://127.0.0.1:5000/all/

# REST API With Flask & SQL Alchemy

<img src="https://www.ncrts.com/public/images/webapp-banner.jpg">
> Form Database CRUD API using Python, Flask, SQL Alchemy and Marshmallow for SIS to register 3 fields, store the regs in a SQLite DB and logs the creation event in a creation.log file. It flashes custom messages for specific event types and errors. I also implemented Basic Authentication using Flask-httpauth.

## How to run it

``` bash
# Install dependencies:
pipenv shell
pipenv install
# Run Server (http://localhost:5000)
python3 app.py
```

## Screenshots
<img src="https://i.imgur.com/64RqYz5.png">
<img src="https://i.imgur.com/Ir2tgHR.png">
<img src="https://i.imgur.com/rKhSUg8.png">
<img src="https://i.imgur.com/Jfy1D1Z.png">
<img src="https://i.imgur.com/MHCzjjC.png">
<img src="https://i.imgur.com/QgGIL3s.png">

## Endpoints

* GET     /         - Homepage
* GET     /create   - Creation page
* POST    /create   - Form data stored
* GET     /all      - Get all records
* GET     /update   - Render page
* POST    /update   - Update Email
* GET     /delete   - Render page
* POST    /delete   - Remove user


## Technologies

* HTML5
* CSS
* Python
* SQLAlchemy
* Flask
* Marshmallow
* Flask-httpauth
* Werkzeug

## Authors
Andres Lopez - [Github](https://github.com/andylopezr) / [Twitter](https://twitter.com/_andy_lopez_)

## License
Public Domain. No copyright protection.
