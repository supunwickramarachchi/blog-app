# Simple Django Blog App

A simple blog application built with Django. This application allows users to view a list of blog posts and view individual post details. Posts can be created and deleted through the Django admin panel.

## Features

- View a list of blog posts
- View individual blog post details
- Simple and clean design

## Installation

1. Clone the repository:
    ```bash
    git clone git@github.com:supunwickramarachchi/blog-app.git
    cd blog-app
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply the migrations:
    ```bash
    python manage.py migrate
    ```

5. Create a superuser to access the admin panel:
    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

1. Access the application by navigating to `http://127.0.0.1:8000/` in your web browser.

2. To manage blog posts, log in to the admin panel at `http://127.0.0.1:8000/admin/` using the superuser credentials you created earlier. From there, you can create, update, and delete posts.

## License

This project is licensed under the MIT License. See the LICENSE.txt file for more details.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

---

Feel free to customize this README file as needed. If you have any questions or need further assistance, let me know!
