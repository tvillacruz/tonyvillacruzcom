---
title: "Cheater Die? Bayes' Theorem"
date: 2019-07-15T23:53:00+01:00
draft: false
type: "project"
hideLastModified: false
summary: "A R Shiny App showing cheat probability of a cheat die in a population. Is a simple demo of Bayes' theorem"
summaryImage: "gambler_roll.png"
tags: ["R","Shiny"]
weight: 3
---

This post demostrates an application of Bayes' theorem into an R and Shiny application.

- [Shiny App](#ShinyApp)
- [Inspirational Resources](#Resource)


# Background:

I came across an interesting probability question that required me to dust off my knowledge of Bayes' theorem in order to solve. For me, there is no better way to understand theory than incorporating it into an application. I decided to work the probability question and model into an R/Shiny application (embedded on this page below). 

The question to solve: 

{{< rawhtml >}}
{{< exercise >}}
A casino die is loaded to roll a six 50% of the time. This is, of course, as opposed to a fair dice that would roll a six 16.7% of the time (1/6).  The cheat die is included in a box of 100 dice.  A gambler choses a random die from the box and procedes to roll 3 sixes in a row.  What is the probabiliity that the die is the cheat? 
{{< /exercise >}}
{{< /rawhtml >}}


<!--https://collaboration133.com/how-to-scale-iframe-content-in-ie-chrome-firefox-and-safari/2717/-->

<a id="ShinyApp"></a>
# R/Shiny App:

The Shiny app below is served from an R server. You can change the inputs on the left to update the graphical and text output. 


<style>

#scaled-frame { width: 100%; height: 750px; border: 5px; }
#scaled-frame {
    zoom: 1;
    -moz-transform: scale(1);
    -moz-transform-origin: 0 0;
    -o-transform: scale(1);
    -o-transform-origin: 0 0;
    -webkit-transform: scale(1);
    -webkit-transform-origin: 0 0;
    border: 5px;
    overflow: scroll;
}

@media screen and (-webkit-min-device-pixel-ratio:0) {
 #scaled-frame  { zoom: 1;  }
}
</style>

<iframe id="scaled-frame" src="https://apps.petedunham.com/shiny/Gambler_Roll/" style="border:3px solid lightgrey;" height=100%></iframe>



# Source Code

{{< rawhtml >}}
            
              <h4>
              <a href="https://github.com/dunhampa/Gambler_Roll" target="_blank">
                <span class="icon"><i class="fa fa-github"></i></span>
                Source code on GitHub
              </a>
              </h4>
         

{{< /rawhtml >}}



<a id="Resource"></a>
# Inspiration Resources:

I came across the blog "The Chemical Statitician" by Eric Cai. He had a related post where he discussed implementing the same problem in R.  This post and related code inspired the Shiny app above:
 


{{< book title="The Chemical Statistician" authors="Eric Cai" image="images/TheChemicalStatistician.png" size="x600">}} 

 Read [Detecting Unfair Dice in Casinos with Bayes’ Theorem](https://chemicalstatistician.wordpress.com/2013/10/30/detecting-an-unfair-die-with-bayes-theorem/)

Eric Cai's post 'Detecting Unfair Dice in Casinos with Bayes’ Theorem' provided inspiration for this Shiny app 

{{</book>}} 






