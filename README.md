# PC Helper — Programmer's Assistant 🤓

A simple desktop application built with **Python**, **CustomTkinter**, and **SQLite**.

PC Helper provides quick access to useful programming websites and keeps track of how many times each website has been opened.

## Features

* 🤖 Open ChatGPT
* 🎥 Open YouTube
* 🧑‍💻 Open Python Documentation
* 📊 Track the number of launches for each website
* 💾 Save statistics in an SQLite database
* 🌙 Dark mode interface

## Technologies

* Python
* CustomTkinter
* SQLite3
* Webbrowser

## How It Works

When the program starts, it creates an SQLite database called `pc_helper.db`.

The database contains an `apps` table with:

* `id` — unique application ID
* `name` — application or website name
* `launches` — number of times it has been opened

When a button is pressed:

1. The corresponding website is opened in the browser.
2. Its launch counter is increased by 1.
3. The statistics on the screen are updated.

## Installation

Install CustomTkinter:

```bash
pip install customtkinter
```

SQLite3 and `webbrowser` are included with Python, so they do not need to be installed separately.

## Run

Run the Python file:

```bash
python main.py
```

## Project Structure

```text
PC-Helper/
│
├── main.py
├── pc_helper.db
└── README.md
```

## Example

The application displays statistics like:

```text
Launch Statistics

ChatGPT: 5
YouTube: 3
Python Docs: 7
```

## Author

Created as a Python learning project.
