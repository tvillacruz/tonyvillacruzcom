---
title: "Inspiration for Creating A Personal Website"
date: 2019-07-15T23:53:00+01:00
draft: false
type: "project"
hideLastModified: false
summary: "I was inspired to create this website in order to take my first step towards becoming a full stack problem solver. Full stack problem solving requires 3 basic concepts: Learn, Apply, Teach. To apply these concepts, I decided to start by learning how to create a website."
summaryImage: "InspirationRationFix2.jpeg"
tags: ["Website","Inspiration"]
weight: 3
---

# Background

I was inspired to create this website in order to take my first step towards becoming a full stack problem solver. 

Before I proceed to discussing my journey of building my website, I want to discuss what it means to be a full stack problem solver. My business partner Pete Dunham and I decided to start a concept that we call **Full Stack Problem Solving**. Full stack problem solving requires doing 3 basic actions: _Learn_, _Apply_, _Teach_.

* **LEARN** - Learning is the first step in the process and can often be the most intimidating. But the key is just be willing to take the first step!

* **APPLY** - Knowledge is great, but only if you can use it. It is important to apply what you know, because in doing so you will unlock the ability to truly master something.

* **TEACH** - This might be the most overlooked part of problem solving. Being able to learn and apply what you know is important, but if the only person who benefits from that knowledge is you, then can you really say it makes a difference? It is this ability to take what you know and teach it to others, that can set you apart from the rest.

Now what does that have to do with me building this website? Well in order to apply these actions, I decided to start by learning how to create a website. My hope is that I can use this as a platform to showcase what I learn and to do it in a way that others can hopefully use to grow themselves!

*To learn more about what it means to be a full stack problem solver, please visit our site https://fullstackproblemsolvers.com*



# Learning How to Build a Website

I had to first begin my journey by taking the time to research what all goes into a website, research how I can learn to do it myself, and find the best platform to apply this new found knowledge. 

I decided to start by talking to my mentor Pete Dunham, who told me that creating a personal website can not only help advance my web developing skills but also be a great place to share experiences, thoughts, and ideas with others. He said the place to start would be to first learn about the idea of "_Open Source_".

Open Source is a term that refers to source code that is released in such a manner that the copyright holder grants users the rights to use, study, change, and distribute the code to anyone and for any purpose. Put another way, open source coding is the concept of building code in a such a way that it is free and available for others to use in order to help them grow themselves as well. It is a concept that allows people to learn from one another by sharing their ideas and discoveries.

A great open source platform for website building is known as Hugo. Hugo is one of the most popular open-source static site generators. They believe that with its amazing speed and flexibility, they can make building websites fun again (Link to Hugo: https://gohugo.io/). Hugo allows web developers to create and upload website templates or "themes" that they have built. These themes can then be downloaded and altered by users to use for their own purposes.

I decided to use Pete's modified version of the [Hugo Refresh by Pete]( https://www.petedunham.com/) theme to begin my research. By being able to download Pete's code I was able to see all of the components that go into making these websites, and use that to learn all of the parts and pieces that go on behind the scenes in order to make a website. Plus, the majority of the themes that are posted in Hugo come with a set of instructions for how to get started and how to start making this template your own. This allowed me to move on to my next step in my FSPS journey, applying this knowledge by building my own website.



# Applying Web Development Skills

Now that I know some of the components needed for website building, I am now ready to start applying that knowledge.

As I mentioned above, I decided to use Pete's modified version of the Hugo Refresh theme as template for my website. Here are some of the steps I took to get started:

	# Create site and cd into it
	hugo new site tonyvillacruzcom && cd tonyvillacruzcom
	
	# Clone the Revised Refresh theme into the Themes folder
	git clone <Git Repo URL>

	# Run the site locally
	hugo server -D

	# Open the site in your browser
	http://localhost:1313

By running the site locally, I was able to make changes to the template to make it my own. Every refresh theme works a little differently, but all have some sort of config document that makes up the landing page content and a content folder that is used for the underlying subsections of the website. Therefore, some of the main sections I made updates to were:

* Updated a lot of the *config.yaml* to add my photo, fix the footer links and add my summary
* Under the content folder I removed the placeholder blogs and projects, and would then replace them in the future with this blog!

Once I had a minimally viable product (MVP) it was time for the site to go live. To start I need to buy a website domain for me to use. There are many websites you can use to search and purchase your own domain. I decided to use [NameCheap]( https://www.namecheap.com/). Now that I had a domain, it is time to deploy my website code to that domain. For this I decided to use [Netlify]( https://www.netlify.com/). Netlify streamlines website deployment and management at every step of the journey – from your first Git push, to the last HTML file in your build. It was quick, easy, and painless to use, I highly recommend!


# Teaching Others by Blogging or In Person Demo

Ahhh the final step. I will keep this last part short and sweet. As I mentioned at the beginning of this blog, it is important to not only learn new things and then apply it, it is also important to make sure you are able to share that knowledge with friends, peers, and the rest of the world. I decided to do that by writing this blog, and my hope is that it inspires others to do the same!


