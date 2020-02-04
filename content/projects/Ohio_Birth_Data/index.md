---
title: "Click-able Map Dashboard: Ohio Birth Data Exploration"
date: 2020-02-03T23:53:00+01:00
draft: false
type: "project"
hideLastModified: false
summary: "A Shiny app using shinydashboard and Leaflet to allow for analysis of county data by clicking on Ohio country map"
summaryImage: "OhioBirthData.png"
tags: ["R","Shiny"]
weight: 2
---


This post discusses using R/Shiny with Leaflet and shinydasbhoard package to make a click-able map. The map is prepped to display popup windows with details and the application updates various plots (ggplot2) based on the county selected.

I had previously built similar mapping type dashboard in Tableau and I wanted to see if same type of dashboard could be built using tools available in the R ecosystem (**hint:** they can!)

# Go To App:

The shinydashboard is best viewed and used in a full tab:
<left>
<div class="action">
        <a href="https://apps.petedunham.com/shiny/Interactive_Ohio_BirthData/" target="_blank" class="button is-primary">
                Click Here to Go to App
            </a>
      </div></left>

# Source Code:

{{< rawhtml >}}
            
              <h4>
              <a href="https://github.com/dunhampa/Interactive_Ohio_BirthData" target="_blank">
                <span class="icon"><i class="fa fa-github"></i></span>
                Source code on GitHub
              </a>
              </h4>
         

{{< /rawhtml >}}

# Example Preview:


<a href="https://apps.petedunham.com/shiny/Interactive_Ohio_BirthData/"><img src="OhioBirthData.png" alt="Bayes Shiny" style="width:100%"></a>
