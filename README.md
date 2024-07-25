# Blog API

## Overview
This project is a RESTful API for a blog application built using Django, Django Rest Framework (DRF), and SimpleJWT for JWT-based authentication.

## Features
User registration and authentication
JWT-based authentication with SimpleJWT
Create, read, update, and delete (CRUD) operations for blog posts
Commenting system for posts
User profile management

## Requirements
Python 3.10+
Django 5.0+
Django Rest Framework 3.15+
djangorestframework-simplejwt 5.3+

## Installation
```
git clone https://github.com/Towet-Tum/Django-Rest-Framework-Blog-Api.git
cd Django-Rest-Framework-Blog-Api
```
### Create Virtual environment and activate
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
### Install the requirements
```
pip install -r requirements.txt
```
### Apply migrations 
```
python manage.py makemigrations
python manage.py migrate
```
### Create super user
```
python manage.py createsupueruser
```
