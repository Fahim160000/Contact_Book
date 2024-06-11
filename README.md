## Contact_Book

Contact_Book is a simple web application built with Django that allows users to create, view, and manage their contacts.

## Features

- User authentication (login, logout)
- Create, view, edit, and delete contacts
- List of all contacts sorted by last name and first name
- Responsive and user-friendly interface

## Installation

### Prerequisites

- Python 3.x
- Django

### Steps

### Clone the repository:

```bash
   git clone https://github.com/yourusername/Contact_Book.git
   cd Contact_Book
```


### Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages: 
```

```bash
pip install -r requirements.txt
Apply migrations: 
```

```bash
python manage.py makemigrations
python manage.py migrate
Create a superuser: 
```

```bash
python manage.py createsuperuser
Run the development server: 
```

```bash
python manage.py runserver 
```

### Visit the application:
```bash
Open your browser and go to http://127.0.0.1:8000/ 
```

## Usage
### User Authentication
- Navigate to /accounts/login/ to log in.
- Use the Django admin interface at /admin/ to manage contacts.

## Managing Contacts
- After logging in, you can add a new contact by clicking the "Add New Contact" link.
- View a contact's details by clicking on their name in the contact list.
- Edit or delete a contact from their detail view.


## Project Structure

```bash
Contact_Book/
├── Contact_Book/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── contacts/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── contacts/
│           ├── contact_list.html
│           ├── contact_detail.html
│           └── contact_edit.html
├── db.sqlite3
├── manage.py
└── requirements.txt
```

## Contributing
- Fork the repository.
- Create a new branch.
- Make your changes and commit them.
- Push your changes to your fork.
- Create a pull request.
   
