# Project: Visualizing Pixar's Roller Coaster

Pixar Animation is one of the most well known animation studios in the world and many people worldwide religiously watch every new released film. With hits like Toy Story, Finding Nemo, Monster's Inc, and A Bug's Life, Pixar's movies are adored by kids for their charming characters and by adults for their wit. To date, Pixar has released 15 movies total (at the time of writing) and its recent movies, like Inside Out, still continue to amaze viewers and critics alike. While Pixar has seen a lot of success, including a successful acquisition by Disney, not every one of their movies have been a hit. We'll explore Pixar's Roller Coaster at the box office.

## Context 
This project is part of Dataquest.io guided projects. Datasets were provided and we were asked to make data exploration in Jupyter Notebook. Each project were constituted of 6 to 8 steps of exploration, analysis, visualization and sometimes machine learning algorithm implementation. Additional steps were given at the end of each project to advance our exploration. The text cells between each code cells are part of the instructions that were provided. It is slightly retouched. For example, instead of 'you', it has been replace by 'we' to improve readability. 

## Install
This project requires Python 3 and the following Python libraries installed:

- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Seaborn](https://pypi.python.org/pypi/seaborn/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 3.x installer.

## Code
All the code is in the notebook `visualizing_pixar_roller_coaster.ipynb`.

## Run
In a terminal or command window, navigate to the top-level project directory Visualizing-Pixar-s-Roller-Coaster/ (that contains this README) and run one of the following commands:

```
jupyter notebook visualizing_pixar_roller_coaster.ipynb
```

or
```
ipython notebook visualizing_pixar_roller_coaster.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.

## Data
The dataset used in this project is included as `PixarMovies.csv`. [Alex Albright](https://github.com/apalbright) has put together a dataset containing critics' ratings and opening weekend revenue for all of Pixar's movies, which you can find on [her Github repo](https://github.com/apalbright/Pixar/blob/master/Pixar.csv). While this is a wonderful starting point, there's a lot more information available for each movie that we can add.

By scraping the data from Box Office Mojo and making some adjustments, we were able to put together the following dataset. The data is up to date as of November 2015 and doesn't contain the updated revenue numbers for Inside Out or any data on The Good Dinosaur.
