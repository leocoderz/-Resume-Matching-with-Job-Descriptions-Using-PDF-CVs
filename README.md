# Resume Matching with Job Descriptions Using PDF CVs

This project is designed to help you match job descriptions with resumes extracted from PDF files. It includes two main components: PDF CV extraction using the `PDFExtractor.ipynb` notebook and resume matching using the `Resume_Matching.ipynb` notebook. Additionally, you'll find two datasets: `resume_data.csv` and `training_data.csv`, which are used for training and testing the matching algorithm.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [PDF CV Extraction](#pdf-cv-extraction)
- [Resume Matching](#resume-matching)
- [License](#license)

## Introduction

Recruiting the right candidate for a job can be a time-consuming process, especially when you have to manually review countless resumes. This project aims to automate the resume matching process by extracting text from PDF CVs and then comparing them with job descriptions using natural language processing techniques.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites installed:

For PDF CV Extraction:
- Python 3.x
- `pypdf` library
- `pandas` library

For Resume Matching:
- Python 3.x
- `pandas` library
- `numpy` library
- `re` library
- `spacy` library
- `sklearn` library
- `string` library
- `transformers` library
- `torch` library

### Installation

To install the required packages, you can use pip:

```bash
pip install pypdf pandas numpy scikit-learn spacy torch transformers
```

## PDF CV Extraction

The `PDFExtractor.ipynb` notebook is designed to extract text from PDF CVs. It uses the `pypdf` library to read PDF files and save the extracted text to a CSV file. To use this notebook, follow the instructions provided within the notebook.

## Resume Matching

The `Resume_Matching.ipynb` notebook demonstrates how to match resumes with job descriptions. It uses natural language processing techniques to preprocess and vectorize text data, and then it calculates the cosine similarity between resumes and job descriptions. This allows you to rank candidates based on how well their resumes match the job requirements.

## License

This project is licensed under the GNU General Public License, Version 2.0. See the [LICENSE](LICENSE) file for details.

Feel free to customize and use this project to streamline your recruiting process. If you have any questions or need further assistance, please don't hesitate to reach out.
