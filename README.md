# Udacity Portfolio Exercise: Starbucks Home Assignment

This goal of this Udacity portfolio exercise was to classify Starbucks customers to decide who is going to receive a promotion. Only those customers, that are most likely to purchase the product, should receive the promotion. 


## Installation

No installation needed, you can simply download the repository from GitHub. 


## Project motivation

This exercise was part of Udacity's Data Science online course and situated at the end of some lessons about experimental design and A/B testing. No solution was provided. 

The two metrics to be maximized are Incremental Response Rate (IRR) and Net Incremental Revenue (NIR). Read more about there description and computation in the notebook's introductory text. 


## Data

Quoting the introductory text of the notebook: 

> The dataset you will be provided in this portfolio exercise was originally used as a take-home assignment provided by Starbucks for their job candidates. The data for this exercise consists of about 120,000 data points split in a 2:1 ratio among training and test files. 



## How to interact

Interestingly, I found that applying StandardScaler worsed the IRR and NIR for KNeighbors. I would like to try other classifiers (SVM, Randomforest), to see if IRR and NIR improve. If you have any ideas about this, every contribution is welcome. 


## Acknowledgments

Thanks to Starbucks for providing the data and to Udacity for providing initial information and comments. 


## Author

Maximilian Müller, Business Development Manager in the Renewable Energy sector. Now diving into the field of data science.


## License

Copyright 2020 Maximilian Müller

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

From opensource.org
