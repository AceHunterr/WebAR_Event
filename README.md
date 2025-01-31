<h1 align='center'>PRE-HULT WebAR-Event</h1>
This website is using django backend. All you need to do is to go through https://docs.djangoproject.com/ so that you get the basic knowledge that how things are working in django.

## Steps to follow ✏️:

1. First of all install Django:

For any system:

```bash
  python -m pip install Django
```

For Archlinux:

```bash
sudo pacman -S python-django
```

2. Clone the repository:

```console
git clone https://github.com/swastkk/WebAR_Event
```

3. Change the directory to WebAR_Event using:

```console
cd WebAR_Event
```

4. Create a virtual environment:

```console
pip install virtualenv
virtualenv dev
```

5. Activate the virtual environment

```console
source dev/bin/activate
```

6. Now install all the packages which are being used in this project:

```console
pip install -r requirements.txt
```

7. Migrate all the database

```console
python manage.py migrate
```

8. Now run the development server:

```console
python manage.py runserver
```
