# Web-Design-Challenge
Data and instructions provided by UC Berkeley Extension Data Analytics Bootcamp.

# Introduction 

The goal of this assignment is to use my newfound HTML, CSS, and Bootstrap 4 knowledge and skills to create a dashboard showing off the analysis I have done. Webpage: https://yuyhong23.github.io/Web-Design-Challenge/.

# Technologies/Libraries

- HTML

- CSS
 
- Bootstrap 4

- Python Pandas

- Jupyter Notebook

- Github pages

# Detailed Instructions/Assignment Background

#### Website Requirements

The website must consist of 7 pages total, including:
- A landing page containing:
    - An explanation of the project.
    - Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

- Four visualization pages, each with:
    - A descriptive title and heading tag.
    - The plot/visualization itself for the selected comparison.
    - A paragraph describing the plot and its significance.

- A "Comparisons" page that:
    - Contains all of the visualizations on the same page so we can easily visually compare them.
    -Uses a Bootstrap grid for the visualizations.
    -The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

- A "Data" page that:
    - Displays a responsive table containing the data used in the visualizations.
    - The table must be a bootstrap table component. Hint
    - The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here

- The website must, at the top of every page, have a navigation menu that:
    - Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
    - Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
    - Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
    - Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

- Finally, the website must be deployed to GitHub pages.

# Files

- Resources folder is where the images and data csv are located.

- Other files are on the front page of this repository.

# Process and Credits

My first assignment using HTML, CSS and Bootstrap. I used class materials and outside resources for reference. For this assignment, I spent a lot of time fixing the styling for the navbar and width for different screen size. After talking to my groupmates and rereading the rubric, I realized that I need to use bootstrap grid to organize the sections, so I had to add that in for all the html and adjust the css file.

Here are the outside resources that I used for this assignment (as well as attempts):

- https://www.w3schools.com/Css/
- https://www.w3schools.com/tags/default.asp
- https://getbootstrap.com/docs/4.3/getting-started/introduction/
- https://developer.mozilla.org/en-US/docs/Web/CSS/font-family
- https://www.w3schools.com/bootstrap/bootstrap_navbar.asp
- https://css-tricks.com/when-using-important-is-the-right-choice/
- https://stackoverflow.com/questions/24420080/change-navbar-text-color-bootstrap
- https://getbootstrap.com/docs/4.0/utilities/colors/
- https://uplandsoftware.com/postup/resources/blog/prevent-your-images-from-showing-gaps-between-each-other/
- https://www.codespeedy.com/converting-csv-to-html-table-in-python/
- https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color
- https://stackoverflow.com/questions/43381596/bootstrap-4-navbar-color
- https://stackoverflow.com/questions/41896043/bootstrap-4-collapsed-navbar-background-color
- https://love2dev.com/blog/html-website-copyright/

