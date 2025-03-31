# 📝 Flaskr - Flask Blog Tutorial App

This is a minimal blog application built using **Flask**, based on the official [Flask tutorial](https://flask.palletsprojects.com/en/latest/tutorial/). It teaches the fundamentals of building web applications with Flask, including:

- ✅ User authentication (register/login/logout)
- ✅ Blog post creation, editing, and deletion
- ✅ SQLite3 database integration
- ✅ HTML templating with Jinja2
- ✅ Unit testing with `pytest`

---

## 🚀 Getting Started

### 📦 Clone this repo

```bash

git clone https://github.com/YOUR_USERNAME/flask_tutorial.git

cd flask_tutorial

🐍 Set up a virtual environment
Using Python:

bash

Copy

Edit

python -m venv .venv

# Windows

.venv\Scripts\activate

# macOS/Linux

source .venv/bin/activate

Or using Conda:

bash

Copy

Edit

conda create -n flaskr-env python=3.10 -y

conda activate flaskr-env

📥 Install the application

bash

Copy

Edit

pip install -e .

If using the source version of Flask:

bash

Copy

Edit

pip install -e ../..

pip install -e .

🛠️ Running the App

🗄️ Initialize the database

bash

Copy

Edit

flask --app flaskr init-db

💻 Run the development server

bash

Copy

Edit

flask --app flaskr run --debug

Open your browser to: http://127.0.0.1:5000

🧪 Running Tests

Install test dependencies

bash

Copy

Edit

pip install .[test]

Run tests

bash

Copy

Edit

pytest

Run tests with coverage

bash

Copy

Edit

coverage run -m pytest

coverage report

coverage html

Then open htmlcov/index.html in your browser.

📁 Project Structure

csharp

Copy

Edit

flaskr/
├── __init__.py        # App factory
├── auth.py            # Authentication blueprint
├── blog.py            # Blog post blueprint
├── db.py              # Database connection + CLI
├── schema.sql         # DB schema
├── static/            # CSS files
└── templates/         # HTML templates

📚 What You'll Learn
How to structure a Flask project

Using Flask Blueprints

SQLite integration with Flask

Templating with Jinja2

Testing Flask apps with pytest

Command-line integration with Flask CLI

🧠 Credits

Based on the official Flask tutorial by the Pallets project.

📜 License
This project is licensed under the MIT License.
