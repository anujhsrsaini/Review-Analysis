# Play Store Review Analysis

This Jupyter notebook reads user reviews of a Play Store app, categorizes them into positive and negative sentiments based on user ratings, and performs topic modeling. Then, data is visualized through word clouds for both positive and negative reviews.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Introduction

This jupyter notebook aims to provide insights into user sentiments and topics discussed in reviews of anything. It specifically focuses on categorizing reviews into conducting topic modeling, and generating word clouds for visualization.

## Features

- Preprocesses reviews by finding important nouns and words used in positive and negative reviews.
- Utilizes Latent Dirichlet Allocation (LDA) for topic modeling.
- Generates word clouds for visualizing topics in positive and negative reviews.

## Getting Started

### Prerequisites

- Python 3.7.9
- Github
- Jupyter notebook usage

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/anujhsrsaini/reviews-analysis.git
2. Navigate to the project directory:
   ```sh 
   cd reviews-analysis
3. Initiate a virtual environment and activate the virtual environment:
   ```sh 
   python -m venv venv
   venv/Scripts/activate
   ```
3. Install the required libraries in the virtual environment
   ```sh
   pip install -r requirements.txt
   ```

### Usage

1. Provide your reviews CSV files in the reviews folder.

***CSV file table should contain content and score column where content is user review and score is user rating.***

You can use code from [this repo](https://github.com/anujhsrsaini/Play-Store-Review-Scraper) to fetch reviews of different apps from play store.

2. Run the jupyter notebook code cell by cell.

3. Examine the generated output, including LDA topics and word clouds for both positive and negative reviews.

### Acknowledgments

Thanks to the developers of NLTK, Gensim, and WordCloud for their excellent libraries.
Special thanks to the open-source community for valuable contributions.


## Authors

- **[Anuj Saini](https://www.linkedin.com/in/anuj-saini-7230a0257/)**