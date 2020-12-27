# tech-app
# Guide on how to create and set up a Dockerized web app using Django REST APIs and ReactJS
Hopefully this will answer *"How do I setup or start a Django project using REST Framework and ReactJS?"*

This is a guide to show you step by step how this can be setup.  If you just want to get started, use the cookiecuter I set up [cookiecutter-django-reactjs](https://github.com/genomics-geek/cookiecutter-django-reactjs).  It basically is a fork of pydanny's cookiecutter, just added the front-end stuff :).

I created this because it was __SUCH__ a pain in the ass setting up a project using all the latest technologies. 
After some research, I figured it out and have it working. The repo that implements this is located [here](https://github.com/genomics-geek/django_reactjs_boilerplate). Feel free to use it as a boilerplate ;)

Main features:
+ Django REST APIs
+ ReactJS with Redux Pattern
+ Webpack module bundler manager
+ Hot Reloading of ReactJS components for quicker development
+ Dockerized

**NOTE: This guide was built using:**
+ Django 1.10.2
+ Django REST Framework 3.4.7
+ NodeJS 6.7.0 with NPM 3.10.7
+ ReactJS 15.3.2
+ Redux 3.6.0
+ Webpack 1.13.2
+ Karma 1.3.0
+ Mocha 3.0.2

## 1. [Setting up your machine](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step01-md)
## 2. [Setup version control with Git](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step02-md)
## 3. [Create dot files for project](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step03-md)
## 4. [Set up PostgreSQL database](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step04-md)
## 5. [Create a Virtual Environment for Python](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step05-md)
## 6. [Create Python requirements and install local dependencies](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step06-md)
## 7. [Setup Django project](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step07-md)
## 8. [Setup NodeJS project](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step08-md)
## 9. [Setup Webpack as front-end module bundler](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step09-md)
## 10. [Wire up Django/ReactJS application](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step10-md)
## 11. [Setup Karma and Mocha for running JavaScript Unittests](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step11-md)
## 12. [Customize NodeJS commands for ease of use](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step12-md)
## 13. [Dockerize application](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step13-md)
## 14. [Add Helpful Utilities for Consuming Django APIs with React](https://gist.github.com/genomics-geek/98929a9e7ba9602fed7bfa4a5a1c5c4e#file-step14-md)