# Blogmax-Django
[![](https://img.shields.io/pypi/pyversions/Django.svg)](https://python.org/downloads/)
[![](https://img.shields.io/badge/django-2.0%20%7C%202.1%20%7C%202.2-success.svg)](https://djangoproject.com/)
[![](https://img.shields.io/apm/l/vim-mode.svg)](https://choosealicense.com/licenses/mit/)

Full-Featured Blog with Django web framework. 

### Screenshots
<img src="https://i.hizliresim.com/3tggkY.png" width="480" height="241"> <img src="https://i.hizliresim.com/aeEe38.png" width="480" height="241"> <img src="https://i.hizliresim.com/ScjgdY.png" width="480" height="241"> <img src="https://i.hizliresim.com/Aa73cx.png" width="480" height="241"> <img src="https://i.hizliresim.com/ygjwfh.png" width="480" height="241"> <img src="https://i.hizliresim.com/7Th7sE.png" width="480" height="241"> <img src="https://i.hizliresim.com/r5oFxc.png" width="480" height="241"> <img src="https://i.hizliresim.com/my0eDT.png" width="480" height="241">

Features 
=
- User Registration
- User Login & Logout
- User Profile
- Create, Update, Edit & Delete Posts
- Comments
- Search
- User Change Password
- Password Reset
- Customized admin panel
- Pagination
- Contact

How To Use
=
## Clone project & Install Requirements
> Make sure you have already installed python3 and git.
```
$ git clone https://github.com/pubuser7/django-blog.git && cd django-blog
$ pip install -r requirements.txt
```
## Migrate & Collect Static
```
$ cd src && python manage.py migrate
$ python manage.py collectstatic
```
## Create Admin User
```
$ python manage.py createsuperuser
```
## Run Server
```
$ python manage.py runserver
```
> Enter your browser http://localhost:8000/. You can login via admin in http://localhost:8000/admin/.

## Add Some Posts
> You can edit posts via admin panel or from corrent user added post.

TODOS
=
- Change Style
- Favourites
- Advanced Categories
- Reply comment
- Search for post any pages
- Create following system
- Popular Users
- Like post
- ...
