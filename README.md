# flask-shop

[![Language](https://img.shields.io/badge/language-python-brightgreen?style=flat-square)](https://www.python.org/)

Hello everyone! This is the repository of shop application on Flask framework.

## Table of contents

- [Table of contents](#table-of-contents)
- [Motivation](#motivation)
- [Build status](#build-status)
- [Badges](#badges)
- [Screenshots](#screenshots)
- [Tech/framework used](#techframework-used)
- [Features](#features)
- [Installation](#installation)
- [Fast usage](#fast-usage)
- [Contribute](#contribute)
- [Credits](#credits)
- [License](#license)

## Motivation

I just want to have more **practice** with Flask, so I took another one tutorial on YouTube.

## Build status

Here you can see build status of [continuous integration](https://en.wikipedia.org/wiki/Continuous_integration):

[![Build Status](https://travis-ci.com/mezgoodle/flask-shop.svg?branch=master)](https://travis-ci.com/mezgoodle/flask-shop)

## Badges

[![Theme](https://img.shields.io/badge/Theme-Shop-brightgreen?style=flat-square)](https://www.google.com/search?q=django+shop&rlz=1C1CHZO_ukUA900UA900&oq=django+shop&aqs=chrome..69i57j0l5j69i60l2.2903j1j7&sourceid=chrome&ie=UTF-8)
[![Platform](https://img.shields.io/badge/Platform-Flask-brightgreen?style=flat-square)](https://www.djangoproject.com/)
 
## Screenshots

- Main page

![Screenshot 1](https://raw.githubusercontent.com/mezgoodle/images/master/flask-shop1.png)

- About page

![Screenshot 2](https://raw.githubusercontent.com/mezgoodle/images/master/flask-shop2.png)

- Add product

![Screenshot 3](https://raw.githubusercontent.com/mezgoodle/images/master/flask-shop3.png)


## Tech/framework used

**Built with**

- [Python](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)

## Features

On the website you can view and add products.

> Also you can add payment system, such as [PayPal](https://developer.paypal.com/demo/checkout/#/pattern/client)

## Installation

1. Clone this repository:

```bash
git clone https://github.com/mezgoodle/flask-shop.git
```

2. Install all dependencies with [pip](https://pip.pypa.io/en/stable/):

```bash
pip install -r requirements.txt
```

## Fast usage

1. Rewrite database:

```bash
python
from app import db
db.create_all()
exit()
```

2. Start the development server:

```bash
python3 app.py
```

## Contribute

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Credits

Credit to tutorial:

- [Video](https://www.youtube.com/watch?v=759C2p3CAA4)

## License

MIT © [mezgoodle](https://github.com/mezgoodle)
