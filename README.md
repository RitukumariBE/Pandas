# 🐼 _Pandas Basics Documentation_

This repository contains notes and practice notebooks covering the fundamental concepts of Pandas, a powerful Python library used for data manipulation and analysis in Python.
It is designed for beginners who want to learn how to work with structured datasets such as CSV and Excel files.

## 📦 Installation

Pandas can be installed using the Python package manager pip.

pip install pandas


If you are using the Anaconda distribution, Pandas is usually pre-installed.
If it is not available, you can install it using:

conda install pandas

## 📥 Importing Pandas

After installation, Pandas is imported in Python using the commonly accepted alias pd.

import pandas as pd


This alias helps keep the code clean and readable while working with Pandas functions and objects.

🧱 Core Data Structures in Pandas

Pandas mainly works with two data structures:

Series – One-dimensional labeled array capable of holding data of any type

DataFrame – Two-dimensional labeled data structure similar to a table with rows and columns

Most data analysis tasks in Pandas are performed using DataFrames.

📂 Reading Data Files

Pandas provides easy-to-use functions to read data from various file formats and load them into a DataFrame.

📄 Reading a CSV File

CSV (Comma-Separated Values) files are one of the most commonly used data formats.

df = pd.read_csv("filename.csv")
