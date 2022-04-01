# advanced-programming-assignment
### University of York, MSc Computer Science with AI, Advanced Programming Summative Assignment

A prototype application that demonstrates how data form CSV data sets can be formatted, cleaned, and used to generate specific outputs, including: 

* A means to load the initial data set (which consists of three CSV files) and translate it into a suitable format, JSON has been selected here. 
* A means to back up the data in this format using either files or a database, preserving the current state of the data when the program is closed, and making it available when the program is reopened. A MySQL database has been used here. 
* A process for cleaning and preparing the initial data set, managing inconsistences, errors, missing values and any specific changes required by the client.
* A graphical user interface(s) for interacting with the data that enables the user to:
    * Load and clean an initial data set (from its CSV format)
    * Load and save a prepared data set (from its translated format)
    * Use the prepared data set to generate outputs and visualisations
    * Manipulate the range of values used to generate output and visualisations

---

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required environment.

```bash
pip install -r requirements.txt
```

---

## Running the programme

To start the application, open a [Jupyter Notebook](https://jupyter.org/) using: 

```bash
jupyter notebook
```

Then open the file 'summative-assignment.ipynb' in the Jupyter Notebook.

--- 

## Project Components

...