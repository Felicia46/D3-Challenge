# D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

Welcome to the newsroom! You've just accepted a data visualization
tasked with analyzing the current trends shaping people's lives, a
interactive elements to help readers understand your findings.

The editor wants to run a series of feature stories about the heal
counting on you to sniff out the first story idea by sifting throu
the Behavioral Risk Factor Surveillance System.

The data set included with the assignment is based on 2014 ACS 1-y
(https://data.census.gov/cedsci/), but you are free to investigate
includes data on rates of income, obesity, poverty, etc. by state.

### Before You Begin

1. Create a new repository for this project called `D3-Challenge`.
repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, create a directory for the D3
to the challenge: **D3_data_journalism**.

4. This homework utilizes both **html** and **Javascript** so be s
be the main files to run for analysis.

5. Push the above changes to GitHub or GitLab.

## Your Task

### Core Assignment: D3 Dabbler (Required Assignment)

![4-scatter](Images/4-scatter.jpg)

You need to create a scatter plot between two of the data variable
vs. Age`.

Using the D3 techniques we taught you in class, create a scatter p
elements. You'll code this graphic in the `app.js` file of your ho
from `data.csv` by using the `d3.csv` function. Your scatter plot 
top of this section.

* Include state abbreviations in the circles.

* Create and situate your axes and labels to the left and bottom o

* Note: You'll need to use `python -m http.server` to run the visu
`localhost:8000` in your web browser.

- - -

### Bonus: Impress the Boss (Optional Assignment)

Why make a static graphic when D3 lets you interact with your data

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

You're going to include more demographics and more risk factors. P
give them click events so that your users can decide which data to
circles' locations as well as the range of your axes. Do this for 
extreme challenge, create three for each axis.

* Hint: Try binding all of the CSV data to your circles. This will
when you click the labels.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values f
the true value without adding another layer of data. Enter tooltip
graphics to reveal a specific element's data when the user hovers 
your circles and display each tooltip with the data that the user 
developed by [Justin Palmer](https://github.com/Caged)—we've alrea
directory.

![8-tooltip](Images/8-tooltip.gif)

* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd
should implement tooltips with d3-tip.

- - -

### Assessment

Your final product will be assessed on the following metrics:

* Creation of a **new** repository on GitHub called `D3-Challenge`
already existing repo.

* Completion of all steps in the core assignment

* Coherency of scatter plot (labels, ticks)

* Visual attraction

* Professionalism

* Ensure your repository has regular commits (i.e. 20+ commits) an

**Good luck!**

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
