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

I came across an interesting probability problem that required me to dust off my knowledge of Bayes' theorem in order to solve.

I won't get into the math since it is available everywhere. The part I wanted to write down is the example for intuition. 

For example: If a die is loaded (is a cheat) to roll a 6 more often, how certain can you be that it is loaded after your roll two sixes in a roll.  Parameters that matter are:

1. How loaded is the dice? For instance, will 6 appear every 3 rolls, every roll, every 2 rolls
2. How many loaded dice is there? Is there only 1 loaded dice out of a million. You would have to be pretty unlucky to pick that one
3. How many rolls produced a 6?



<!--https://collaboration133.com/how-to-scale-iframe-content-in-ie-chrome-firefox-and-safari/2717/-->
<style>

#scaled-frame { width: 100%; height: 750px; border: 0px; }
#scaled-frame {
    zoom: 1;
    -moz-transform: scale(1);
    -moz-transform-origin: 0 0;
    -o-transform: scale(1);
    -o-transform-origin: 0 0;
    -webkit-transform: scale(1);
    -webkit-transform-origin: 0 0;
}

@media screen and (-webkit-min-device-pixel-ratio:0) {
 #scaled-frame  { zoom: 1;  }
}
</style>

<iframe id="scaled-frame" src="https://apps.petedunham.com/shiny/Gambler_Roll/"></iframe>










