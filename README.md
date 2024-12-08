# CSV to JSON Converter

This repository contains a tool for converting CSV files to JSON documents using Python and Pandas. The folder structure mirrors the database's table structure, where each folder represents a table, and it contains CSV files as the source data. 

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Example](#example)

## Features
- Converts all CSV files to JSON documents by default.
- Allows selective conversion of specific tables using command-line arguments.
- Uses environment variables to specify source and target directories for flexibility.

## Prerequisites
Ensure you have the following installed:
- Python 3.7 or higher
- `pandas` library

You can install `pandas` by running:
```bash
pip install pandas
```
## Installation
```bash
git clone https://github.com/yourusername/csv-to-json-converter.git
cd csv-to-json-converter
```

## Usage
- To convert all tables
  ```bash
  python app.py
  ```
- To convert selective tables
  ```bash
  python app.py '[\"table_name1\", \"table_name2\"]'
  ```

## Setting Enviroment Varialbles
- $Env: SRS_BASE_DIR = 'source'
- $Env: TGT_BASE_DIR = 'target'



