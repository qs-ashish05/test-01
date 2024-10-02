# Steps to run project

### 1. Install Dependencies
First, install the required Python packages:

```bash
pip install django
pip install urllib3
pip install pybase64
pip install matplotlib
pip install pandas


### 2. Run Database migrations
```bash
python manage.py makemigrations
python manage.py migrate

### 3. Create Super Uer (Admin)
```bash
python manage.py createsuperuser


### 4. To Generate Sample Data
``` bash
python manage.py generate_data

### 5. To launch Website
``` bash
python manage.py runserver


