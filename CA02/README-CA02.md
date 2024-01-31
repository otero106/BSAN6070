# CA02: Spam Email Detection Using Naive Bayes Classification Algorithm

<i>
Luis Otero
<br>
BSAN 6070
<br>
January 30, 2024
<br>
https://github.com/otero106/BSAN6070
</i>
<br>

## Description

Utilizing a supervised machine learning algorithm called Naive Bayes to build a model that can determine whether an email is spam or not based on the features/words. The project is completed in Google Colab in order to make the user experience easier and to have the users easily access the necessary data.

## Python Libraries Needed

* os
* NumPy
* Counter
* Scikit-Learn
* google.colab

## Software

* Python
    * Version 3.9.13
* Google Colab

## Data Sources

* train-mails: Professor Brahma
* test-mails: Professor Brahma

## Installation and Executing Program

### Data
* Use the following URL to access the folder containing the training emails
    * https://lmu.box.com/s/2stwq4m01vfch6hmks6vfos2y81ndvj8
    * Click "Download" at the top right
* Use the following URL to access the folder containing the emails for testing
    * https://lmu.box.com/s/2stwq4m01vfch6hmks6vfos2y81ndvj8
    * Click "Download" at the top right
* Save both folders onto your Google Drive

### Google Colab
* Open the notebook as a new project in Google Colaboratory (colab.research.google.com)
* Run the first two blocks of code under "Loading Libraries and Accessing Google Drive". 
    * Once you run the second block, a pop-up window will appear.
    * Permit Google Colab to access your Google Drive
    * Sign in to your Google account and allow permissions (check all boxes)
```
drive.mount('/content/drive')
```
* Scroll down to section titled "Load Training and Test Emails"
    * On the left-hand side of the screen, select "Files" and open "drive" then "MyDrive"
    * Navigate to the "train-mails" folder and click on the three dots to the right of the folder
    * Select "Copy Path." 
    * Erase the old file path between the apostrophes and paste your train-mails file path
    * Do the same with "test-mails"

* You are now all set up! Click "Run All" at the top.

## Acknowledgments/References

* Professor Brahma
* [A simple README.md template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [Naive Bayes Classifiers](https://www.geeksforgeeks.org/naive-bayes-classifiers/)
* [Scikit Learn - Classification with Naive Bayes](https://www.tutorialspoint.com/scikit_learn/scikit_learn_classification_with_naive_bayes.htm)
* [How to Use Google Colab to Work with Local Files](https://saturncloud.io/blog/how-to-use-google-colab-to-work-with-local-files/)
