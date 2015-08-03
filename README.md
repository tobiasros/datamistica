# Introduction

It is now possible to collect a large amount of data about human creativity monitoring social networks and photo-/video-sharing websites such as [Facebook](https://www.facebook.com/tobias.rosenberger.7), [Picasa](http://picasaweb.google.com/tobiasrosenberger80) and [Vimeo](https://vimeo.com/tobiasrosenberger). Together with the collection & mining of exhibition/artwork announcements, descriptions and reviews in W3, these digital platforms are ideal candidates to serve the "quantified artist" movement -- a group of creative technologists who take measurements about their work output and public appearance regularly to improve their artistic practice, to find patterns in their works, or simply because they are tech geeks. But these data remain under-utilized both because the raw data are scattered to the three w's and there is a lack of statistical methods and software for processing and interpreting the data.

This assignment makes use of data from one specific media artist ([Tobias Rosenberger](http://tobiasrosenberger.de/)). Data has been collected at sporadic intervals since 2003, more regulary since 2007. 

# Data

The data for this assignment can be downloaded from this Github-repository. Important events included in these datasets are:

- **exhibitions**: An incomplete listing of exhibitions (solo/group), theatrical performances, screenings, lectures and artist talks the artist participated in
- **links**: An incomplete listing of uniform resource locators (URLs) that refer to blogs, archives, festivals, institutions etc. that are related to the work of the artist
- **press**: An incomplete listing of uniform resource locators (URLs) that refer to texts and press that are related to the work of the artist 
- **works**: An artist-curated listing of artworks created since 2003

The datasets are stored in comma-separated-value (CSV) files and there are a total of 162 observations in these datasets.

# Assignment

This assignment will be described in multiple parts. You will need to write a report that answers the questions detailed below. Ultimately, you will need to complete the entire assignment in a single R markdown document that can be processed by knitr and be transformed into an HTML file.

Throughout your report make sure you always include the code that you used to generate the output you present. When writing code chunks in the R markdown document, always use echo = TRUE so that someone else will be able to read the code. This assignment will be evaluated via artist assessment so it is essential that your artist evaluator is able to review the code for your analysis.

For the plotting aspects of this assignment, feel free to use any plotting system in R (i.e., base, lattice, ggplot2)

Star/fork/clone the GitHub repository created for this assignment. You will submit this assignment by pushing your completed files into your forked repository on GitHub. The assignment submission will consist of the URL to your GitHub repository and the SHA-1 commit ID for your repository state.

NOTE: The GitHub repository also contains the dataset for the assignment so you do not have to download the data separately.

# Loading and preprocessing the data

Show any code that is needed to

1. Load the data (i.e. read.csv())

2. Process/transform the data (if necessary) into a format suitable for your analysis

# What is mean total number of event types the artist participated in per year?

For this part of the assignment, you can ignore the missing values in the dataset.

1. Make a histogram of the total number of exhibitions/talks/performances participated in per year.

2. Calculate and report the mean and median total number of exhibitions (group + solo), talks (including lectures) and performances (theater + screenings) per year.

