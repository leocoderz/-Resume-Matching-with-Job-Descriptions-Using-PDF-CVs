# Resume Matching with Job Descriptions

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)

This repository contains code and resources for matching resumes with job descriptions using PDF CVs and PDFExtractor. The project includes two Jupyter notebooks (`ResumeMatching.ipynb` and `PDFExtractor.ipynb`), as well as sample CSV data files (`resume_data.csv` and `training_data.csv`) for training and testing the model.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [Data Files](#data-files)
- [License](#license)

## Introduction

Matching resumes to job descriptions is a crucial step in the recruitment process. This project aims to automate this process by extracting text from PDF resumes using PDFExtractor and comparing it with job descriptions to find the most suitable candidates.

Key features of this project include:
- Extraction of text from PDF resumes.
- Matching extracted text with job descriptions.
- Ranking candidates based on their suitability.

## Requirements

To run the code in this repository, you'll need the following dependencies:

- Python 3.x
- Jupyter Notebook
- PDFExtractor library
- Pandas
- Scikit-Learn

You can install these dependencies using `pip`:

```bash
pip install jupyter pandas scikit-learn
```

For PDFExtractor, please follow the installation instructions provided in the `PDFExtractor.ipynb` notebook.

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/resume-matching.git
cd resume-matching
```

2. Install the required dependencies as mentioned in the "Requirements" section.

3. Open the Jupyter notebooks and follow the instructions provided in the notebooks:
   - `PDFExtractor.ipynb`: This notebook demonstrates how to extract text from PDF resumes using PDFExtractor.
   - `ResumeMatching.ipynb`: This notebook shows how to match extracted resume text with job descriptions and rank candidates.

4. Use the provided CSV files (`resume_data.csv` and `training_data.csv`) for testing and training your model.

## Notebooks

### PDFExtractor.ipynb

This notebook provides step-by-step instructions for extracting text from PDF resumes using PDFExtractor. It covers:
- Installation of PDFExtractor
- Loading and extracting text from PDF resumes
- Cleaning and preprocessing extracted text

### ResumeMatching.ipynb

This notebook demonstrates how to match extracted resume text with job descriptions and rank candidates based on their suitability. It includes:
- Loading resume and job description data
- Text preprocessing and feature extraction
- Building a matching model
- Ranking candidates

## Data Files

### resume_data.csv

This CSV file contains sample resume data that can be used for testing and experimentation. Each row represents a resume with relevant information.

### training_data.csv

This CSV file contains training data for building and training the matching model. It includes pairs of resumes and job descriptions along with labels indicating whether they are a good match or not.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use, modify, and distribute this code for your own purposes.
