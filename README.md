# Django CV Generator

This project is a Django-based web application for generating professional CVs (resumes) in PDF format.

## Features
- User-friendly interface for entering CV details
- PDF generation of CVs
- Customizable templates
- Secure user authentication

## Getting Started

### Prerequisites
- Python 3.8+
- Django 4.0+
- (Recommended) Virtual environment

### Setup
1. Clone the repository:
   ```bash
   git clone git@github.com:insomniac1712/Django-CV-generator.git
   cd Django-CV-generator
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the development server:
   ```bash
   python manage.py runserver
   ```

## Usage
- Visit `http://127.0.0.1:8000/` in your browser.
- Register or log in to create and download your CV.