# Web-Design-Challenge

In this assignment I used HTML and CSS to create a dashboard featuring the Latitude vs. X analysis of weather. Note that thing assignment is displaying results from prior analysis done in python-api-challenge through Github pages using HTML, CSS, and Bootstrap.

Instructions

Create a website by using either the visualizations that was created for the Python-APIs Challenge or the weather data and images that are provided for this Challenge. To do so, use the considerations and website requirements that the following subsections describe. 

A landing page that contains the following elements:
1. An explanation of the project.
2. A link to each visualization page. For these, a sidebar should contain a preview image of each visualization. Clicking an image should take the user to that visualization.

Four visualization pages, stored in the visualizations folder, each with the following elements:
1. A descriptive title and a heading tag.
2. The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the assets/images folder.
3. A paragraph describing the visualization and its significance.

A comparisons page that does the following:
1. Contains all the visualizations on the same page so that people can easily compare them.
2. Uses a Bootstrap grid for the visualizations. This grid must contain two visualizations across a medium or large screen and one visualization across an extra-small or small screen.

A data page that displays a responsive table containing the data that the visualizations use, as follows:
1. The table must be a Bootstrap table component.
2. The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a to_html method that generates an HTML table from a Pandas DataFrame. To learn more, see pandas.DataFrame.to_html Links to an external site. in the official Pandas documentation.

At the top of every page, your website must have a navigation bar that does the following:
1. Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.
2. Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualization page.
3. Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.
4. Is responsive (via media queries). Note that the navigation bar must resemble the one in the screenshots in the Navigation Bar section. In particular, notice the background color change.
5. Your website must be deployed to GitHub Pages: https://github.com/cjallow01/Web-Design-Challenge
