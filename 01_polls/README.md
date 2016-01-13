

Polls project using

Python v2.7.10
Django v1.9.1

### Notes

- outer `mysite/` root directory: Container for the project. Name doesn’t matter to Django; can be renamed.
- `manage.py`: Command-line utility for the Django project.
- inner `mysite/` directory: Actual Python package for the project. Its name is the Python package name used to import anything inside (e.g. mysite.urls).
- `__init__.py`: An empty file that identifies this directory as a Python package.
- `settings.py`: Settings/configuration for this Django project.
- `urls.py`: URL declarations for the project.
- ` wsgi.py`: Entry-point for WSGI-compatible web servers to serve the project.
