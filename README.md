# TF-IDF-implimentation 

# Coding-Problem-Search-Engine
forgot the question name of a particular website. No worries, go to our website and search for your questions by putting relevant keywords and hitting search; 

# Search Engine

A search engine that allows users to search for questions based on their query. The search engine consists of three main stages: web scraping, TF-IDF algorithm, and a Flask web application.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- Web scraping: The search engine scrapes question data from websites such as LeetCode, Codeforces, and CodeChef (But in this, I've only scrapped data from Leetcode for simplicity) using Beautiful Soup and Selenium.
- TF-IDF algorithm: It implements the TF-IDF algorithm to find potential documents (questions) related to the user's query.
- Web application: The search engine is integrated into a web application built with Flask and HTML, allowing users to search for questions and view the results.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/NCSAHITH/Code-Eureka.git

2. Install dependencies:

- Make sure you have beautiful soup and selenium installed in your workspace

  ```shell
  pip install bsoup
  ```
  ```shell
  pip install selenium

- if getting error after installing the libraries

  ```shell
  pip install -user bsoup selenium
  ```
for installing it globally

- For hosting the backend locally go to Website/Backend

  ```shell
  python -m flask --app app run
  ```
- Now you are good to go, now the website will be hosted on http://127.0.0.1:5000

## Usage

1. Perform a search:

- Enter a query in the search box.
- The search engine will process the query using the TF-IDF algorithm and display relevant questions as results.
