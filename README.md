# CS50W Week 3: Django - Tasks, New Year, and Hello Apps

This repository contains my projects from Week 3 of Harvard's **CS50 Web Programming with Python and JavaScript** course. This week's focus was on learning the fundamentals of the Django web framework.

## Topics Covered

- Django project structure
- Creating and linking apps
- URLs and routing
- Templates and template inheritance
- Forms and handling POST requests
- Django's built-in development server

## About the Apps

### `hello/`
A simple app that demonstrates the basics of Django, including:
- Defining views
- URL routing
- Returning HTML responses directly from views

---

### `newyear/`
This app checks whether or not today is New Year's Day. It uses:
- Python's built-in `datetime` module
- Conditional logic in views
- Template rendering to display different messages depending on the date

---

### `tasks/`
A basic task manager app that allows users to add and view tasks. It demonstrates:
- Template rendering with context data
- Handling both `GET` and `POST` requests through Django forms
- Template inheritance using a shared layout
