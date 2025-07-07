# hello-django

# Warm up
- https://code.visualstudio.com/docs/python/environments
- https://docs.djangoproject.com/en/5.2/faq/install/#faq-python-version-support
- https://dashboard.render.com/web/new?newUser=true

# Init
```bash
$ pyenv virtualenvs 3.11.13 3.11.13-djang

$ pyenv global 3.11.13-djang

$ python -m pip install Django

$ pyenv versions
  system
  3.8.20
  3.11.13
  3.11.13/envs/3.11.13-djang
* 3.11.13-djang --> /Users/diginori/.pyenv/versions/3.11.13/envs/3.11.13-djang (set by /Users/diginori/.pyenv/version)

$ 
$ python -m django --version
5.2.4
```

# Hello
```bash
$ source .venv/bin/activate
$ pdm add dJango
$ django-admin startproject mysite .
$ python manage.py runserver
```