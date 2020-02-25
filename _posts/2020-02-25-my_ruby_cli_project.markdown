---
layout: post
title:      "My Ruby CLI Project"
date:       2020-02-25 23:24:57 +0000
permalink:  my_ruby_cli_project
---


Something that really fascinates me is the way similar ideas and concepts can be found across different cultures. A fun example of such a concept is the dumpling, which appears ubiquitously in every corner of the world. For my Ruby CLI project, I thought it would be fun to make an application showcasing these fun little pockets of food. Dumplings the app allows the user to choose a world region, a country in that region, and a dumpling from that country to read a small blurb about that dumpling. Dumplings instantiates a total of 6 region, 42 country, and 65 dumpling objects that interact via the “belongs to” / “has many” relationship. 
	
To build my application, I scraped information from three different websites. The majority of the content for Dumplings came from an article titled, “The Best 65 Dumplings Around The World,” which provided the names, countries of origin, and descriptions of the dumplings. Despite looking like a normal, well-organized website, the webpage for this article turned out to be really tricky to scrape. I came across several strings that refused to be split no matter what I did and caused important attributes to equal nil. After several days without any progress, I realized I needed to start working on the actual CLI, so I resorted to some desperate measures (e.g. deleting incomplete data hashes, hardcoding missing data). I combined this patchwork of information with the data I scraped from the two other websites and ended up with a clunky and slow app. Thankfully, my awesome educational coach Morgan saved the day and figured out a regex sequence for me to use, which allowed me to rewrite a lot of the methods.

On a completely different note, I really enjoyed the task of nesting information about objects and making the app react to user input. As a challenge, I added various “back” commands to Dumplings, which allow the user to go back to previous screens. These commands work by storing and deleting object instances in an array that belongs to a CLI class object. While I’m sure this is not an elegant or efficient way to store memory, it works perfectly fine for my simple app, which only needs to remember four objects at most. Overall, I’m pretty happy with the way my first project turned out and I’m looking forward to the feedback process! 





