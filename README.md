
# PyFlaskHelloWorld

Application web simple Python et Flask.

* Installer les deps : `pip install -r requirements.txt`
* Start app : `python3 -m flask run`
* Lien du site : **http://localhost:5000**

## Conteneurisation
* Build de l'image : `docker build --tag py-flask-helloworld .`
* Run image : `docker run -d -p 5000:5000 py-flask-helloworld`
