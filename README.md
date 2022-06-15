# Starbucks-Capstone-Project
How do we know if a offer will be received well by a customer of Starbucks? Is there a way to predict if a customer will complete a offer and therefore make transactions?

## Table of contents

- [Motivation](#motivation)
- [Installations](#installation)
- [File descriptions](#file-description)
- [Results](#results)
- [Licensing, Authors, Acknowledgements](#author)

## Motivation
By sending out random offers to random cusomers we might do more harm than good. Is there a way to find out which customers need special offers so that they will make at least one transaction?


## Installation
For running the code you only need numpy, pandas, matplotlib, seaborn and sklearn. Python 3.* was used for the attached files. If you use anything esle you might need to make some changes to the notebook.

## File description<a name="file-description"></a>
There are three json files (all available in the file 'data'). They contain the data I used to built my model.
1. portfolio.json
2. profile.json
3. transcript.json

Furthermore there is a pyhton-script: Starbucks_Capstone_notebook.ipynb
This is the main file I used to make my analysis, implement an algorithem and present the results to you.


## Results
After analysing the data (by going through all the necessary steps: Posing Question, Wrangle Data (Gather, Assess and Clean the Data), Exploring the Data, Conclusion). I came to the conclusion to try the Random Forest approch for finding out, if an offer will be completed (and therefore making more transactions). By looking at the confusion Matrix afterwards, I noticed that the model will work fine for the prediction of offer completed and offer viewed. Which was our main goal. This can be read in the blog-post [here]  (https://medium.com/@julia.gilly/starbucks-capstone-project-using-random-forest-to-predict-if-an-offer-is-completed-or-not-by-a-6245cdb5b6ab )


## Licensing, Authors, Acknowledgements<a name="author"></a>

Can't take credit for the data used for this project. The data was provided by Udicity (and Starbucks). For further information please go to their webpage:  https://www.udacity.com/

Otherwise feel free to use my code.
