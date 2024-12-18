# python-packages
Packages to install for odoo

```
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.11
python3.11 --version
```
after that
```
sudo apt install python3.11-venv
```
and create your virtual environment
```
python3.11 -m venv venv
```
and install odoo requirements.txt
```
source venv/bin/activate
pip install -r odoo/requirements.txt
```
---------------------------------------------------
if faced any problem during requirements insalling, use below command:
```
sudo apt install python3.11-dev libxml2-dev libxslt1-dev zlib1g-dev libsasl2-dev libldap2-dev build-essential libssl-dev libffi-dev libmysqlclient-dev libjpeg-dev libpq-dev libjpeg8-dev liblcms2-dev libblas-dev libatlas-base-dev
```
and then retry installing requirements.
