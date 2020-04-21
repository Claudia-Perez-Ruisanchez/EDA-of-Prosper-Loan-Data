
![](loanData.jpg)
# Exploratory Data Analysis of Prosper Loan Data

## Introduction

Prosper Marketplace is a  company in California dedicated to the peer-to-peer lending industry. Prosper Funding LLC, operates Prosper.com, a website where individuals can either invest in personal loans or request to borrow money. It is America's first peer-to-peer lending marketplace, with over $7 billion in funded loans.
As part of this  project we are going to explore  data from Prosper that could lead us to find patterns in our data to ask questions like:

* What factors affect a loan’s outcome status?
* What affects the borrower’s APR or interest rate?

and all the questions that we will find in this process.

## File Description

The dataset that we are going to work with is stored in prosperLoanData.csv. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
All the codes of our exploratory analysis are stored on the Jupyter Notebook exploratory_template.ipynb. The notebook slide_deck_template.ipynb contains some visualization to explain our analysis. The archive slide_deck_template.slides.html contains a presentation that was generated from slide_deck_template.ipynb with the help of the archive output-toggle.tpl obtained [here](https://github.com/damianavila/blog/blob/master/posts/hide-the-input-cells-from-your-ipython-slides.ipynb) and typing the following in the terminal:

jupyter nbconvert slide_deck_template.ipynb --to slides --post serve --template output_toggle
