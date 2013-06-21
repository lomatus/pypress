A team blog based on [Flask](http://flask.pocoo.org/)
===

This project is forked form [pypress](https://github.com/laoqiu/pypress) by laoqiu

A very good sample for newbie of Flask which come from newsmeme

Purpose of this fork is to make this project relive

#Version road map

## Version 0.1.0

Use blueprint instead of older module for Flask 0.10.* and newer

Fixed bug of Upload

## Version 0.1.1

Convert to to Sina Appliaction Engine

1. Storage - OS
2. Mail - SAE mail
3. MySQL configure

# Version 0.1.*

Please post issue or suggestion on github to route the development

===

##Install

###Prerequisite

	pip install -r requirements.txt

###Custom the Configuration
	
	pypress/config.cfg

###Sync database

	python manage.py createall

###Run

	python manage.py runserver

##Example
###Create Users

Admin:

	python manage.py createcode -r admin

Create three members in a batch:
	
	python manage.py createcode -r member -n 3

###Signup
	
	http://localhost:8080/account/signup/
