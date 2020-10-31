![screenshot of badge](https://img.shields.io/badge/license-MIT-blue.svg)

# E-Commerce Back End App

## Description

---

A database app that makes use of sequelize and mysql to manipulate a database using different endpoints to test the application's API routes. This app makes use of the Insomnia app to test out those routes.

## Table of Contents

---

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

---

- Download the source code from my repo and unzip the file onto your computer.
- Install all necessary dependencies by using the command: `npm install sequelize mysql2 express dotenv`

## Usage

---

- Update `.env` file with your username and password information for mysql.
- Run `mysql -u root -p` and enter the password to run the program schema.
- Enter `source db/schema.sql` to load your database into mysql workbench. Enter "quit" to exit the program.
- After you can enter `npm run seed` to seed your information, and launch it using `npm start`.
- Open up the Insomnia app.

Walkthrough video:

[E-Commerce app](https://drive.google.com/file/d/1GcoivmIjMQvRjXE1V1ngkDEUvMsMa7Wm/view?usp=sharing)

![screenshot #1 of app in use](./insomnia1.PNG?raw=true)

![screenshot #2 of app in use](./insomnia2.PNG?raw=true)

## License

---

MIT License
Copyright (c) [2020]
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

## Contributing

---

Create any issues, Fork to my repo, Create any pull requests pending approval.

## Questions

---

Want to see more projects ? Check out my github at [https://github.com/patinoman].

Please email me at patino.hector@gmail.com for additional questions.
