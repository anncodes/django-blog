# Blog App Built with Django

This project is a simple blog application built using Django following the tutorial provided by Real Python. The application allows users to create, read, update, and delete blog posts.

The tutorial can be found at [Real Python - Build a Blog from Scratch with Django](https://realpython.com/build-a-blog-from-scratch-django/).

## Features

- User authentication and authorization.
- Create, update, and delete blog posts.
- View a list of all blog posts.
- Individual pages for each blog post.
- Admin panel for managing posts and users.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/blog-app-django.git


2. Navigate to the project directory:<br>
'cd blog-app-django' <br>

3. Create a virtual environment:

python -m venv venv
Activate the virtual environment:

On Windows:

bash
Copy code
venv\Scripts\activate
On macOS and Linux:

bash
Copy code
source venv/bin/activate
Install the project dependencies:

bash
Copy code
pip install -r requirements.txt
Apply migrations:

bash
Copy code
python manage.py migrate
Run the development server:

bash
Copy code
python manage.py runserver
Access the application in your web browser at http://localhost:8000.

Contributing
If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Create a new Pull Request.
License
This project is licensed under the terms of the MIT license. See the LICENSE file for more information.

Acknowledgements
Real Python for the excellent tutorial on building a blog with Django.
