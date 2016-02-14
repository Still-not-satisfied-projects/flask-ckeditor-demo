flask-ckeditor-demo
===

## demosite:

## Step 1: use [mana](https://github.com/neo1218/mana) to create a simple flask project

    $ mana init FCDemo

## Step 2: integrated CKEditor and create upload floder

    $ cd app/static
    $ git clone https://github.com/neo1218/Configured-CKEditor.git
    $ mkdir upload

you can change the default config by editing config.js

## Step 3: install flask-ckeditor

    $ pip install flaskckeditor

## Step 4: 

    <script src={{ url_for('static', filename='ckeditor/ckeditor.js') }}></script>

......
