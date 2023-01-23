# Web-Design_Challenge

# Unit 11 Homework: Web Visualization Dashboard

# Background
Data is more powerful when we share it with others! Let's use what we've learned about HTML and CSS to create a dashboard featuring the analysis that we've done, as captured in the following image:

![image](https://user-images.githubusercontent.com/111756299/214082142-fb8a1fea-d482-4ada-98e8-e0a37c943a83.png)


# Final Webpage available using link below:

https://amarrai99.github.io/Web-Design-Challenge/


# Instructions
For this homework assignment, you'll create a website by using visualizations that were created in your Python-APIs homework, or you can use the weather data provided.
As you build this dashboard, you'll create individual pages for each plot and a way to navigate between them. These pages will contain the visualizations and des. You will also build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

# Website Requirements

The website must consist of seven pages in total, including:


A landing page containing the following elements:


An explanation of the project


Links to each visualizations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.




Four visualization pages, stored in the visualizations folder, each with the following elements:


A descriptive title and heading tag.


The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the assets/images folder.


A paragraph describing the plot and its significance.




A "Comparisons" page that does the following:


Contains all of the visualizations on the same page so they can easily be compared with each other.


Uses a Bootstrap grid for the visualizations.

The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.





A "Data" page that displays a responsive table containing the data used in the visualizations.


The table must be a Bootstrap table component. Refer to the Bootstrap documentation for how to use responsive tables.


The data must come from exporting the .csv file as HTML or by converting it to HTML. Try using a tool that you already know: Pandas. Pandas has a method, appropriately called to_html, that allows you to generate an HTML table from a Pandas DataFrame. To learn more, review the documentation.




At the top of every page, the website must have a navigation menu with the following elements:


It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.


It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.


It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.


It should be responsive (using media queries). The navigation bar must be similar to the screenshots in the "Navigation Menu" section (notice the background color change).


Finally, the website must be deployed to GitHub Pages.
Once finished, submit links to 1) the deployed app and 2) the GitHub repository.
Ensure your repository has regular commits and a descriptive README.md file.

# Considerations


You may use the weather data you collected for the WeatherPy section of your Python-APIs Homework, or you may use the included cities dataset and pull the images from the assets folder.


You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the Bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.


You must deploy your website to GitHub Pages, with the website working on a live, publicly accessible URL as a result.


Make sure to use a CSS media query that uses Bootstrap and/or @media for the navigation bar.


Make sure that your website works at all window widths or sizes.


Feel free to take some liberty in the visual aspects, but keep the  core functionality the same.
