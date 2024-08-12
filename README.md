# PYTHON REVIEW
## 1. Reading and writing to a text file
### Tasks:
1. Reading a list of names from a file and printing each name.
2. Appending new lines of text to an existing file.

## 2. Reading and writing to Word document
### Tasks:
1. Extracting all the headings from a word document.
2. Creating a new Word document with a table containing student names and their grades.
#### Using `python-docx` library
```python
pip install python-docx
```
```python
from docx import Document
```

## 3. Reading and writing to Excel sheet
### Tasks:
1. Reading data from an Excel sheet and priniting its content.
2. Creating a new Excel sheet and adding products with their prices and quantities to it.
#### Using `openpyxl` library
```python
pip install openpyxl
```
```python
from openpyxl import load_workbook, Workbook
```

## 4. Making HTTP requests
### Tasks:
1. Fetching and displaying JSON data from an API.
2. Submitting a form using POST request.
#### Using `requests` library
```python
pip install requests
```
```python
import requests
```

## 5. Aschyncronous programming
### Tasks:
1. Asynchronous program that waits for 3 seconds and then prints a message.
2. Running multiple tasks concurrently and printing the time taken to complete them.
#### Using `asyncio` library
```python
import asyncio
```

## 6. Web scraping
### Tasks:
1. Scraping a website and extracting all titles.
2. Scraping a website and extracting all links.
#### Using `requests` and `BeautifulSoup` libraries
```python
pip install requests
pip install beautifulsoup4
```
```python
import requests
from bs4 import BeautifulSoup
```

## 7. Discord Bot
### Tasks:
1. Discord bot that echoes the message sent by the user.
2. Discord bot that sends a random joke to the user.
#### Using `discord.py` library
```python
pip install discord.py
```
```python
import discord
```

## 8. Multithreading and Multiprocessing
### Tasks:
1. Multithreading program that downloads multiple images concurrently.
2. Multiprocessing program that calculates the sum of numbers in a large list by dividing the task among multiple processes.
#### Using `threading` and `multiprocessing` libraries
```python
import threading
import multiprocessing
```
