# FitPal: A Fitness Tracker
## Purdue University Krannert School of Management
## MGMT 59000-B08: Using R For Analytics Final Project

Contained herein is our final project for the Summer 2021 Using R for Analytics course, the FitPal app.

## Outline
- Part 1 - Overview 
- Part 2 - Architecture
- Part 3 - Steps to Use App
- Part 4 - Access the deployed App
- Part 5 - Dependencies

## 1. Overview 
![FitPal-Logo_MedGreenBackground](https://github.com/ajbrillembourg/fitpal-fitness-tracker/blob/1c013b8ba690fb5afe0c7be8964a2a47dd9d37b9/FitPal-Logo_MedGreenBackground.png)

As part of our Using R for Analytics final project, we had the freedom to choose any topic and build a shiny app that satisfied a particular business or customer need. Given that the health and fitness industry is growing fast, we considered options within this sector and to try and capitalize on the demand for fitness technology. We have created an app that displays health data, predicts whether the user will meet their fitness goals, and prescribes recommendations on how to obtain those goals based on the user’s progress. 

Our app requires the user to upload their fitness device data (Fitbit, Apple Watch, etc) and we use R’s Shiny package to display their fitness progress. Ideally, we could either find ways to allow the user to upload their data through individual app's API which we see as one of the main upgrades to our application.

## 2. Architeture
![FitPal_Architecture](https://github.com/ajbrillembourg/fitpal-fitness-tracker/blob/1c013b8ba690fb5afe0c7be8964a2a47dd9d37b9/FitPal_Architecture.png)

Given the nature of Shiny in the R programming language, the app is divided into a user interface (UI) and the server code. For the application where data is uploaded and manipulated, the UI and Server code are written using R's shiny. For the home page user interface, the UI code is written in HTML, CSS, and Javascript while the server code is written in R. Finally, the app is deployed over R shiny server.

Logos, charts, and video were created/edited using Canva and the presentation was created using MS PowerPoint.

## 3. Steps to Use App
![FitPal_FlowChart](https://github.com/ajbrillembourg/fitpal-fitness-tracker/blob/1c013b8ba690fb5afe0c7be8964a2a47dd9d37b9/FitPal_FlowChart.png)

The app can be accessded easily using the 3 simple steps shown in the image.

## 4. Access the deployed App 
The deployed app is accessible at https://fitpalapp.shinyapps.io/home/
You can also view our recorded presentation at https://youtu.be/_GdWHs-xsBg

## 5. Dependencies:
```R

library(shinythemes)
library(shiny)
library(shinyWidgets)
library(shinydashboard)
library(dashboardthemes)
library(dplyr)
library(DT)
library(ggplot2)
library(XML)
library(reshape2)
library(lubridate)
library(scales)
library(ggthemes)
library(ggrepel)
library(plotly)
library(readxl)
library(bslib)
library(writexl)
library(tidyr)
```

