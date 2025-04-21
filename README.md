# eBird API Dashboards

The following was created for my Oakland University MIS 5470 Practical Computing for Data Analytics course final project.

This project aimed to use R to create a Quarto website for exploring area bird sightings.

All data contained in this project was obtained from the [ebird.org](https://ebird.org/home) Web API. The Cornell Lab of Ornithology and National Audobon Society began ebird.org to allow users worldwide to document bird sightings. For this particular project, I only included Michigan data.

This code creates Quarto dashboards in R and publishes them via GitHub Pages and GitHub Actions. The URL to the finished site can be found [here](https://haleymcdowell.github.io/pfw-dashboard/).

The bones of this dashboard were created with help from the fantastic tutorial series on creating Quarto dashboards in R and publishing them via GitHub Pages and GitHub Actions by Melissa Van Bussel. Her series can be found [here](https://melissavanbussel.github.io/spotify-dashboard/tutorial.html). Her dashboard site can be viewed [here](https://melissavanbussel.github.io/spotify-dashboard/).

Packages used in the creation of this dashboard include Observable Plot, gt, httr2, and tidyverse.

The GitHub repository can be found [here](https://github.com/haleymcdowell/pfw-dashboard).

# Significant Files
**index.qmd** - A Quarto document containing the code for the website's [Home](https://haleymcdowell.github.io/pfw-dashboard/) page.<br>
**dashboard.qmd** - A Quarto dashboard containing the code for the [Recent Sightings](https://haleymcdowell.github.io/pfw-dashboard/dashboard.html) page of the website. The data in this dashboard is from Genesee County, Michigan only.<br>
**notable_obs.qmd** - A Quarto dashboard containing the code for the [Notable Observations](https://haleymcdowell.github.io/pfw-dashboard/notable_obs.html) page of the website. The data in this dashboard is from Michigan only.<br>
**_quarto.yml** - Code specifications for website.<br>
**custom.scss** - Code for all formatting. <br>
**publish.yml** - Located in the .github/workflows folder, contains the code for publishing via GitHub Pages and GitHub Actions.