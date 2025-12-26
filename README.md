# MultiMosaic

MultiMosaic is a Flask-based multi-page website that serves as a corporate-style platform with dedicated pages for home, about, services, and contact. It uses Bootstrap for layout, Font Awesome for icons, Animate.css for animations, and a custom stylesheet for additional styling. The application is fully server-rendered using Jinja templates.

---

## Overview

The application provides a simple, maintainable structure suitable for showcasing an organization or brand. It includes:

* A homepage with introductory content
* An about page describing the organization
* A services page displaying offerings using styled cards
* A contact page layout
* A consistent navigation bar, footer, and layout shared via a base template

---

## Features

* Flask application with multiple routes
* Clean and responsive UI layout
* Bootstrap styling
* Font Awesome icons integration
* Animate.css transitions
* Custom CSS enhancements
* Organized template inheritance using `base.html`

---

## Technology Stack

**Backend**

* Python
* Flask

**Frontend**

* HTML (Jinja Templates)
* Bootstrap
* Font Awesome
* Animate.css
* Custom CSS

**Deployment / Runtime**

* gunicorn (listed dependency)

---

## Project Structure

```
MultiMosaic
│
├── app.py                     # Main Flask application
├── requirements.txt           # Python dependencies
│
├── templates/                 # Jinja templates
│   ├── base.html
│   ├── index.html
│   ├── about.html
│   ├── services.html
│   └── contact.html
│
└── static/
    └── css/
        └── custom.css         # Custom styling
```

---

## Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd MultiMosaic-main
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate     # Linux / macOS
venv\Scripts\activate        # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Application

### Development

Run the Flask application:

```bash
python app.py
```

The application starts in debug mode and is available at:

```
http://127.0.0.1:5000
```

---

## Routes

* `/` – Home page
* `/about` – About page
* `/services` – Services page
* `/contact` – Contact page

---

## Notes

* No database or authentication is implemented.
* There is no configuration file or environment variable usage.
* The application is ready to be served using Flask or a WSGI server such as gunicorn.

---

## License

This repository does not include a license file.
