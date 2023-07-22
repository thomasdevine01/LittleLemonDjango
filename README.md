
# Little Lemon Website

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you set up and run the Django app on your local machine for development and testing purposes.

### Prerequisites

- Python 3.x
- pip
- Django 

### Installation

1. Clone the repository to your local machine:
   
   ```git clone https://github.com/thomasdevine01/LittleLemonDjango.git```


2.  Create and activate a virtual environment (optional but recommended):
   `python -m venv venv`
   `source venv/bin/activate` 
    
3.  Install project dependencies:
 `pip install -r requirements.txt` 
    
4. Run database migrations:
 `python manage.py migrate` 
    
5.  Start the development server:
  `python manage.py runserver` 
    
The app will be available at [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your web browser.
    

## Usage

This is a simple Django project. I created this specifically for the backend. The front-end design was prebuilt. It has a SQLite DB, admin page, and a working template system.

## Contributing

This is an open source project. I am also open to Pull Requests!

## License

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
