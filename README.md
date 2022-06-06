# R-Analysis-of-a-AirFrance-Case
<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case">
  </a>

<h3 align="center">Airbnb analysis using NLP and visualization using Tableau</h3>

  <p align="center">
    Analysis of an Airbnb database from Mongo using R for NLP and Tableau to project these insights
    <br />
    <a href="https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case/issues">Report Bug</a>
    ·
    <a href="https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This is a group project, in which we first connected to a cluster of Mongo DB to access a sample of Airbnb data including the listing description, location, property type, review scores, amount of listings, # of bedrooms and bathrooms, and Superhost status. Initially R was used to connect to Mongo DB, running a script for NLP analysis and other precise analysis that couldn't be done on Tableau such as average price overall. At the same time, the initial csv extracted from the database was used to carry a visualization analysis on Tableau to visualize insights not considered on R. Finally compiling both analysis in a report included [here](https://github.com/Dpolar96/Group-Text-Analytics-project-with-R/blob/Group-Project/Report/Combined%20assessment%20report%20(1).pdf).
<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [RStudio IDE](https://www.rstudio.com/products/rstudio/download/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.
1. Line 9  must be updated to reflect local directory.

### Prerequisites

In order to run the code code from this project the following libraries are needed.
* readxl
* ggplot2
* tidyverse
* gapminder
* scales
* dplyr
* ggpubr

### Installation

In case these packages are not installed, please run the following lines of code.
  ```sh
  install.packages("readxl")
  install.packages("ggplot2")
  install.packages("tidyverse")
  install.packages("gapminder")
  install.packages("scales")
  install.packages("dplyr")
  install.packages("ggpubr")
  ```

<!-- CONTACT -->
## Contact

Diego Polar - dpolar76@gmail.com

Project Link: [https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case](https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
I thank and appreciate the help of my group members during the ellaboration of this project:
* [Diana Aycachi](https://www.linkedin.com/in/diana-aycachi-78882480/)
* [Allesandro Casella](https://www.linkedin.com/in/alessandro-casella-97953b197/)
* [Kevin Farjallah](https://www.linkedin.com/in/kevin-farjallah/)
* [Vivian Soo](https://www.linkedin.com/in/vivian-soo-8446641b7/)
* [Madhuri Thackeray](https://www.linkedin.com/in/madhuri-thackeray-05168b14a/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[issues-shield]: https://img.shields.io/github/issues/Dpolar96/R-Analysis-of-a-AirFrance-Case.svg?style=for-the-badge
[issues-url]: https://github.com/Dpolar96/R-Analysis-of-a-AirFrance-Case/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/diego-polar-velasquez-3bbbb9154/
[product-screenshot]: images/screenshot.png
