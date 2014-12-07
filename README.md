adeezer
============
###What is it
This script helps to automate downloading tracks from Deezer with [dezeer.link](http://deezer.link/)

###How to install
* Install Firefox browser
* Clone the repository
* It is recommended to use it with virtualenv. Create virtual environment and activate it:
```bash
virtualenv env
```
```bash
source ./env/bin/activate
```
* Install dependencies:
```bash
pip install -r requirements.txt
```

###How to use
To download all tracks from playlist run:
```bash
python adeezer.py -p <playlist_id>
```
To download all tracks from album run:
```bash
python adeezer.py -a <album_id>
```
All tracks will be downloaded to `<HOME>/Downloads/<item_id>`
