[Click here to see webpage](https://dalismo.github.io/Web-Design-Challenge/index.html)

# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![image](https://user-images.githubusercontent.com/78628287/123146336-be84f980-d42b-11eb-99d6-21d7337a490c.png)

### Before You Begin

1. Create a new repository for this project called `Web-Design-Challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, add your **html** files, as well as your **static** folder. Your `index.html` should be the landing page that the user first sees. DO NOT keep your files inside the Starter Files folder. Copy them out and put them directly in your repository. `index.html` must be at the top level of your repository (not in any subdirectory)

4. Push the above changes to GitHub or GitLab.

5. Deploy to GitHub Pages.

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:

![image](https://user-images.githubusercontent.com/78628287/123146430-d6f51400-d42b-11eb-862d-1a13e5cfca6a.png)

Small screen:

![image](https://user-images.githubusercontent.com/78628287/123146443-dc525e80-d42b-11eb-8905-65941e14e24a.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![image](https://user-images.githubusercontent.com/78628287/123146483-ed9b6b00-d42b-11eb-8525-e2971ea574a4.png)

Small screen:

![image](https://user-images.githubusercontent.com/78628287/123146499-f3914c00-d42b-11eb-935c-d28a094832ec.png)

#### <a id="data-page"></a>Data page

Large screen:

![image](https://user-images.githubusercontent.com/78628287/123146521-fb50f080-d42b-11eb-8735-64cd1d5e2b06.png)


Small screen:
![image](https://user-images.githubusercontent.com/78628287/123146540-0146d180-d42c-11eb-9307-bfa67965976b.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![image](https://user-images.githubusercontent.com/78628287/123146569-0ad03980-d42c-11eb-9a0b-4ea8031d669c.png)

Small screen:

![image](https://user-images.githubusercontent.com/78628287/123146599-0f94ed80-d42c-11eb-91ee-4e063b3c49bb.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![image](https://user-images.githubusercontent.com/78628287/123146619-16236500-d42c-11eb-9772-27cd3a1b943b.png)

Small screen:
![image](https://user-images.githubusercontent.com/78628287/123146644-1cb1dc80-d42c-11eb-8f6b-90cf55da66c8.png)

