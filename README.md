# KaziFasta
Kazifasta is a web application that aims at providing a platform for casual labourers to showcase their skills and get hired.
Kazifasta aims to improve hiring efficiency, enhance accessibility, build trust, support economic growth, and increase convenience for both employers and workers, offering significant benefits to Kenya’s casual labor market.

Features
User Authentication: Sign up, log in and log out functionalities
Recipe Management: create, view, and delete recipes
Comments: Users can comment on the accounts of the casual labourers to rate them
client profiles: clients can log in, filter and browse thru the profiles of the casual labourers

Getting Started
Prerequisites
Python 3.8+
Flask
PHP,MySQL, SQLite or any other SQLAlchemy-supported database
Installation
Clone the repository

https://github.com/stanly08/KaziFasta.git

Navigate to the project directory:

cd dish-discovery

Create a virtual environment:

python3 -m venv venv

Activate the virtual environment:

on Windows:
venv\Scripts\activate

on macOS and Linux:
source venv/bin/activate

Install the dependencies:

pip install -r requirements.txt

Set up the database:

./database.sh

Start the Flask development Server:

flask run



KaziFasta/
│
├── app/
│ ├── **init**.py
│ ├── forms/
│ │ ├── login.py
│ ├── models/
│ │ ├── **init**.py
│ │ ├── user.py
│ │ ├── worker.py
│ │ ├── booking.py
│ ├── routes/
│ │ ├── **init**.py
│ │ ├── worker_routes.py
│ │ ├── booking_routes.py
│ ├── static/
│ ├── templates/
│ │ ├── base.html
│ │ ├── index.html
│ │ ├── login.html
│ │ ├── register.html
│
├── migrations/
│
├── tests/
│ ├── test_routes.py
│ ├── test_models.py
│
├── .env.example
├── config.py
├── run.py
├── requirements.txt
└── README.md




Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.

Authors
Gloria Kitondo
Daniel Muuo
Stanly Anasi
Kelvin
