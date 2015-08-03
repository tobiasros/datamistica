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

# What is mean total number of public events the artist participated in per year?

For this part of the assignment, you can ignore the missing values in the dataset.

1. Make a histogram of the total number of exhibitions/talks/performances the artist participated in per year.

2. Calculate and report the mean and median total number of exhibitions (group + solo), talks (including lectures) and performances (theater + screenings) per year.

# How many artworks did the artist create per year?

1. Make a panel plot containing a time series plot of the year-interval (x-axis) and the average number of artworks created, averaged across the different types (y-axis).

2. Is there any relation to the number of public events the artist participated in?

# What is the visually most attractive artwork that the artist created?

1. Watch at least 10 videos of the artist on [Vimeo](https://vimeo.com/tobiasrosenberger). Browse through his [Picasa Web Albums](http://picasaweb.google.com/tobiasrosenberger80).

2. Compare your findings with the exhibition history and his artwork record. What could be possible conclusions?

# Will the future career sucess of the artist be remarkable?

1. Find a mathematical model that supports the theory that Tobias Rosenberger will have a more than remarkable future career in the field of Virtual Reality.

2. Which additional extra data could be used to flesh out this prediction?

3. Design a simple shiny app that let collectors, curators, critics and the artist himself explore this additional data in an interactive way.

# Submitting the Assignment

To submit the assignment:

1. Commit your completed datamistica.Rmd file to the master branch of your git repository (you should already be on the master branch unless you created new ones)

2. Commit your datamistica.md and datamistica.html files produced by processing your R markdown file with the knit2html() function in R (from the knitr package)

3. Publish your shiny app on shinyapps.io and commit your completed app.R file to your git repository 

4. If your document has figures included (it should) then they should have been placed in the figure/ directory by default (unless you overrode the default). Add and commit the figure/ directory to your git repository.

5. Push your master branch to GitHub.

6. Submit the URLs to your GitHub repository and the shiny app for this assignment to info@tobiasrosenberger.de

In addition to submitting the URLs for your GitHub repository and the shiny app, you will need to submit the 40 character SHA-1 hash (as string of numbers from 0-9 and letters from a-f) that identifies the repository commit that contains the version of the files you want to submit. You can do this in GitHub by doing the following:

1. Go into your GitHub repository web page for this assignment

2. Click on the "?? commits" link where ?? is the number of commits you have in the repository. For example, if you made a total of 10 commits to this repository, the link should say "10 commits".

3. You will see a list of commits that you have made to this repository. The most recent commit is at the very top. If this represents the version of the files you want to submit, then just click the "copy to clipboard" button on the right hand side that should appear when you hover over the SHA-1 hash. Paste this SHA-1 hash into the email-title when you submit your assignment. If you don't want to use the most recent commit, then go down and find the commit you want and copy the SHA-1 hash.

Good luck!

