<!DOCTYPE html>
<html>
<body>

<h1>Getting Started with Django</h1>

<h2>What is Django?</h2>
<p>Django is a high-level Python web framework that simplifies web development by providing a clean and pragmatic design. It encourages rapid development and clean, maintainable code.</p>

<h2>Prerequisites</h2>
<p>Before you start with Django, make sure you have the following prerequisites installed:</p>
<ul>
    <li><strong>Python:</strong> Django is a Python framework, so you need to have Python installed on your system. You can download it from <a href="https://www.python.org/downloads/">Python's official website</a>.</li>
    <li><strong>Virtual Environment (optional but recommended):</strong> It's good practice to create a virtual environment to isolate your Django project's dependencies. You can install the <code>virtualenv</code> package using pip and create a virtual environment for your project.</li>
</ul>

<h2>Installing Django</h2>
<p>You can install Django using pip, Python's package manager:</p>
<pre><code>pip install Django</code></pre>

<h2>Creating a Django Project</h2>
<p>To create a new Django project, use the following command:</p>
<pre><code>django-admin startproject projectname</code></pre>
<p>This will create a project directory with the necessary files and settings.</p>

<h2>Running the Development Server</h2>
<p>Navigate to your project directory and run the development server:</p>
<pre><code>cd projectname
python manage.py runserver</code></pre>
<p>This starts a development server at <a href="http://127.0.0.1:8000/">http://127.0.0.1:8000/</a> by default.</p>

<h2>Creating an App</h2>
<p>In Django, you can create multiple apps within a project to organize your code. To create an app, use the following command:</p>
<pre><code>python manage.py startapp appname</code></pre>

<h2>Setting Up the Database</h2>
<p>Django uses a built-in ORM (Object-Relational Mapping) to work with databases. Configure your database settings in the <code>settings.py</code> file. By default, Django uses SQLite for development.</p>
<p>To create database tables based on your app's models, run migrations:</p>
<pre><code>python manage.py makemigrations
python manage.py migrate</code></pre>

<h2>Creating Views and Templates</h2>
<p>- Views define the logic for handling HTTP requests. Create views in your app's <code>views.py</code> file.</p>
<p>- Templates are HTML files that define how the data is presented. Store templates in your app's <code>templates</code> directory.</p>

<h2>URL Configuration</h2>
<p>Map URLs to views in your app's <code>urls.py</code> file. Include these URL configurations in the project's <code>urls.py</code> file.</p>

<h2>Running Tests</h2>
<p>Django makes it easy to write and run tests for your application. Use <code>python manage.py test</code> to run your tests.</p>

<h2>Deployment</h2>
<p>When you're ready to deploy your Django project, you'll need to configure your production settings, choose a web server (e.g., Gunicorn), and set up a production-ready database (e.g., PostgreSQL).</p>

<p>These are just the basics to get started with Django. As you delve deeper into Django development, you'll explore features like authentication, forms, middleware, and more.</p>

<p>For more detailed documentation and tutorials, refer to the <a href="https://docs.djangoproject.com/">Django Official Documentation</a>.</p>

</body>
</html>
