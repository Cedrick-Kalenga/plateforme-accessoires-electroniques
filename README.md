# Plateforme de vente d'accessoires électroniques

Plateforme e-commerce développée avec Django.

## Installation
```bash
git clone https://github.com/ton-username/plateforme-accessoires-electroniques.git

cd plateforme-accessoires-electroniques

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate

python manage.py showmigrations 

# si showmigrations ne fonctionne pas essayer avec python manage.py makemigrations 

python manage.py runserver
