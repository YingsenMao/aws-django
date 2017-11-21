The packages required are:
* Python 3.4
* pip
* virtualenv
* awsebcli

First create a virtual environment called eb-virt
```
virtualenv eb-virt
```
Activate the environment by
```
eb-virt\Scripts\activate
```
install the package by
```
pip install django==1.9.12
```
If get a *PermissionError: [WinError 5] Access is denied*, try
```
python -m pip install django
easy_install django
```
List all libraries installed, run
```
pip freeze
pip list
```
