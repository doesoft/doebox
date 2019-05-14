# Doebox

Cloudbased filemanager powered by Django

[![Python Django](https://img.shields.io/badge/Python-Django-blue.svg)](https://www.djangoproject.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


- [Doebox](#Doebox)
  - [Getting Started](#getting-started)
    - [Installation](#installation)
  - [Running Locally](#running-locally)
  - [Todo](#todo)

## Getting Started

Clone the repo

```bash
    # SSH
    git clone git@github.com:doesoft/doebox.git
    # HTTPS
    git clone https://github.com/doesoft/doebox.git
```

Activate virtual environment. All project work should be done in virtualenvs and virtualenv names must be added to gitignore

### Installation

#### From Make File
- You could easily run from project directory to setup project or follow through
```bash
    make
```

#### Step by step Setup

- Install the requirements

```bash
    # install pipenv
    sudo pip3 install pipenv

    # install requirements
    pipenv install
```


Run migrations before starting the django-server

```bash
    python manage.py migrate
```

## Running Locally

To view the API locally on port 8000

```bash
    python manage.py runserver 8000
```


## Todo

See [TODO](TODO.md) 


