## TO genarate Requirement.txt
# for check only : pip freeze
$ pip freeze  
$ pip freeze > requirement.txt 
<br> It will list out all the dependencies for the project 

## to install all the dependecies from requirements.txt
$ pip install -r requirement.txt 
$

## to uninstall all the dependecies from requirements.txt
$  pip uninstall -r requirements.txt -y
$
<br><br>

# For Docker:(requirements.txt)
# example: (visit: https://pypi.org/)
```
Django>=2.1.0,<2.2.0
# or 
# Django==3.2
djangorestframework>=3.8.2,<3.9.0

```
