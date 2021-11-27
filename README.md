An ecommerce application built with django as a part of Patika.dev django bootcamp program.

## Prerequisites

 - python 3.8+
 - PostgreSQL 10

## Setup

 - Create a dedicated database and an authorized user in PostgreSQL
 - Install the required packages listed in [`ecommerce/requirements.txt`](ecommerce/requirements.txt)
 - Create a copy of [`default.env`](ecommerce/default.env) in the same directory and rename it as `.env`
 - Fill the `.env` file. You may use the following command to generate a `SECRET_KEY` to fill the corresponding field in the file.

`python -c 'from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())'`

## Run

`python manage.py runserver`