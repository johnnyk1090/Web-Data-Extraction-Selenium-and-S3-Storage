<img src="assets/banner.svg" width="100%" alt="Web Data Extraction to the Cloud. A configurable scraper for UK supplement retailers, from search bar to cloud storage and a database.">

## The idea

Scrape **any UK supplement website that has a search bar**, then land the results in the cloud: product data as JSON and images with unique IDs in **Amazon S3**, and tabular data in a relational database (Amazon RDS) through SQLAlchemy.

## What is inside

1. **Decorators** for timed, retried page interactions
2. A **pivottablejs** GUI to explore the data stored on your path
3. A small **user interface** (tkinter dialogs) for the run's settings and credentials
4. **Universal functions** for all supplement websites, working as a control panel
5. Creation of **local folders** for saving multiple datasets
6. **Continuous scraping** of a given website
7. **Amazon RDS and S3** for the stored information: JSON files and images with unique IDs

## Run it

Prerequisites:

```bash
pip install selenium
pip install tk
pip install pivottablejs
pip install pandas
```

Then run [`scraper.py`](scraper.py). The AWS and database credentials are asked for at runtime in dialogs and are never stored in the code.

## Built with

`Python` · `Selenium` · `pandas` · `SQLAlchemy` · `boto (S3)` · `tkinter` · `pivottablejs`

<br>

<p align="center"><sub><a href="https://github.com/johnnyk1090">← back to the profile</a></sub></p>
