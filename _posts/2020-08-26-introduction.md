---
title:      Hello World! And welcome Data-Science.lt
date:       2020-08-26 14:00:00 +02:00
author:     Justas Mundeikis
layout:     post
permalink:  /2020/04/31/hello-world
image:    /assets/2020/08/26/cowsay.png
thumbnail: /assets/2020/08/26/thumb.cowsay.png
categories:
  - General
tags:
  - Blog
---
**Hello World! - is probably the first thing, that every beginner programmer learns to print out, be it in a Terminal (command line interface), be it in Python, C... and even in R, the command print(“Hello World!”) is often the first one introduced to newcomers. In this initial blog post I would like briefly to explain, who I am, why and what about this blog will be.**<!--more-->

First let me tell you something about me, or

# Who am I

I am an economist by teaching (University of Bonn (Germany) graduate), but now living for about 6 years already in my birth country - Lithuania. I have worked as data analyst in different companies (Maxima (retail sector), Gjensidige (insurance sector) and I have started doing PhD in economics and have taught Data-Science to undergraduate students.

Myself, I switched around 2-3 years ago to Linux as I got tired of Windows 10 and not having a product, but being a product myself. I have tried different flavors of Linux (Linux Mint, Ubuntu, Lubuntu, Arch), but my main goal was always to increase my productivity, decrease maintenance time and just to have a simple, working and reliable solution. About 3 years ago, I also started learning R, as it became obvious, that without it, I could never do the data analysis needed to complete my PhD studies. In the previous years I touched many topics - HTML, CSS, C, C++  that I needed for different projects and right know I am starting to learn Python and its vast possibilities. Being a PhD student teaches one thing - to be able to self-study some new and difficult topic and then to be able to teach that topic / explain it comprehensively to other students.

So I am not an IT guru...

![](/assets/2020/08/26/guru.jpeg)

... so I do mistakes, I learn and I share my knowledge.

# Why this blog / channel?

During my self-studies of Linux, R, learning to play (or program) Arduino and Raspberry I saw one issue for all newbies, who are looking into the topic of **data-science** - there are plenty of materials: books, ebooks, youtube videos, web academies etc. but most of them usually deal with a single aspect of the whole process. You can either learn Linux (and either too much, or too little of it), or you can learn programming, or statistics, but I never found a source where one would have a full curriculum of what is needed.

So I decided to give it a try and start this blog / [youtube](https://www.youtube.com/channel/UCKDWshSCpVu31ObVq2vI9_g) channel (besides having my blog [Lithuanian-Economy.net](lithuanian-economy.net)) where I could show for all newbies where to start, what to learn first, how to solve issues and how everything - Linux, R, Python, statistics are inter-dependent in the everyday work-life of a data-scientist.


# Content

I could also start with a question “What is Data-Science about”. There is no clear cut definition of it. In [Wikipedia you can find following sentence:](https://en.wikipedia.org/wiki/Data_science) “Data science is an inter-disciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from many structural and unstructured data”.  

I do have a bit more broader understanding of a data-science... In my view, a data-scientist is a person who can engage in all steps of data analysis: from data collection (including data transmission, data storage), to data analysis (exploratory data analysis, building models, verifying hypothesis) and showcasing the results (including building simple web-pages if needed to reach the target audience).

In the figure below I show all the “tools” a data-scientist should be able to apply or deploy in order to complete his task

![](/assets/2020/08/26/data_science_tools.png)

* **Linux** in my view is an essential tool and I strongly suggest everybody switches from Windows to Linux, not only the ones, who are interested in learning data-science. But Linux for data-scientist is even more important - it builds up some basic knowledge about command line interface which is very useful when starting programming, it also allows to have a very stable, secure and up to date OS and software. The maintenance of software (keeping everything up to date) is much easier and every Linux installation delivers some powerful GNU tools (sed, curl - just to name few), Windows users can only dream about. Bash-scripting simplifies a lot of work, be it for automating some work on the computer or scrapping web-pages. Built in SSH allows communication with other computers, such as Raspberry, distance-work on servers, as well as simplified communication with ones Github account.

* **Git and Github** are essential tools for data scientists and academics alike. It allows backing up  data (.csv files), code (.R, .pi) and documents (in academics usually written with LaTeX), further using Github allows for collaboration with others and even blogging (this blog is build  using Jekyll in combination with Github Pages).

* **R and Python** are power-horses, that allow to complete almost every possible task, from exploratory data analysis, model building, forecasting to machine learning, web-scrapping, web building and AI.  For sure, one has to gain knowledge in methods such as **Statistics** and **Econometrics** to understand what one is doing (what are the assumptions for using a specific method are, what to do, it these assumptions are violated etc.)

* **Raspberry Pi** and **Arduino** are very nice tools to play with and to learn basics. If one crashes the operating system of a Raspberry, one can reflash the SD card and restart. Arduino helps to understand how computers work, and simplifies the introduction into many topics such as  *for/if/while* loops. Arduino coding language is similar to C, and C and C++ can be used in R to increase the performance (or write own packages). But these tools are not only for playing and learning, they are very useful in building basics of data collection and data transmission.

Here an example of all the tools combined:

>Image you are a data-scientist, who needs to analyze COVID19 spread in a country. Different hospitals and medical centers use different software, there is no centralized way to aggregate the everyday statistics. You could program Raspberry Pies and deliver one to each hospital, so that in every hospital, every day, a person could fill out a spreadsheet with COVID19 statistics and Raspberries would do the rest: transform the data, connect to main server (maybe also A Raspberry) transfer the data. Server would combine and save all data to  a single database. Then you could access the data using SQL on daily basis, analyze the data and model the spread of the virus and present your work to political officials, write reports using LaTeX (or RMarkdown) and maybe even build a website for general public with open data access for other researchers.

This is what this blogsite and Youtube channel will be about - learning step by step all of the necessary tools for a data-scientist to by able to engage and solve real life problems.

# Prerequisites

* Knowledge: NONE! Neither in programming, nor in mathematics or statistics. The whole idea here is to build up all of the basics, that are needed.
* Hardware: on many forums there are questions such like “What PC/ Notebook is good enough for data science?”. In this blog/channel for at least next two years, we will not engage in heavy machine learning, which would require a good graphics card. But **R** is **R**AM hungry, so your PC or NB (notebook) should have at least:

  * 8 GB of RAM
  * Intel Pentium i5 processor
  * internet connection

To give you a glimpse into what my current working machine is:

PC:
* DELL Optiplex 790
* Intel© Core™ i7-2600 CPU, 3.40GHz × 4
* 12 GB RAM
* 1 TB (1000GB) SSD and 1 TB HDD (used to backup SSD)
* Radeon HD 6450 (for machine learning I will have to upgrade my graphics card)
* 2 x 23 inch monitors

Which looks something like this:

![](/assets/2020/08/26/dell.jpeg)

My notebook:
* Lenovo Thinkpad T440S
* 8 GB RAM
* 250 GB SSD


YES that’s it! I even consider buying the new [Raspberry Pi 4 with 8 GB RAM](https://www.berrybase.de/raspberry-pi-co/raspberry-pi/boards/raspberry-pi-4-computer-modell-b-8gb-ram) to prove, that one can do data analysis with it. Especially given the possibility now to boot if from a SSD drive.

![](/assets/2020/08/26/raspberry.jpeg)


In data science the own hardware does (almost) never matter, what does matter is your code. If you have a data set, that cannot be worked with - take a subset of data, write the code correctly and then offload the work to an external processing site (for example to a cloud computing service). So what does matter is the quality of the code. If your code works correctly with a small sample data, you always will be able to find a processing plant, that will be able to crunch the full data set.

Some advices:

* **DONT BUY NEW HARDWARE**, buy used and older one
  * you can still upgrade it (change HDD to SDD) and probably increase RAM up to 16 GB
  * buying older hardware saves you 2/3 to 3/4 of the price of a new hardware although the reduction in processing power is negligible. You can find an older Dell Optiplex machine with i7-4700K processor for around 200 €/$, whereas the i7-10700K costs itself around 400 €/$. Is the new processor better? Yes for sure. Does it matter when you learn coding and do data analysis? Not really. So save the money (and environment) and re-use hardware.
* Dell / Lenovo vs custom build or other brands? I prefer Dell and Lenovo office machines (Optiplex, Thinkpad series and alike) for one reason only: though they are not (were not) build for high power, they were build for longevity. My Optiplex is about 8 years old and works like charm (maybe it is also Linux :D )
* Buy a PC instead of notebook: better performance and better upgrade ability
* Buy mini tower (MT) as it enables you to change hardware more easily and has better ventilation / cooling

![](/assets/2020/08/26/dell_sizes.jpeg)

# The right sequence of bloposts / channel videos

If you are an absolute newbie, what is the "correct" order to learn everything? Here my suggestion and also the order how I will develop this blog / youtube channel:

1. Linux: (~3-4 months) path
* From Windows to Linux
* Command line interface & GNU programs
* Bash scripting
* Different editors (Nano, Sublime, Atom)

2. Version control system (~1-2 months):
* Git
* Github
* HTML and CSS + Github pages

5. Literature and scientific documents (~ 2 months)
* google-scholar
* Mendeley
* Jabref
* LaTeX

6. Data-science
 * with R (~12 months) or
 * with Python (~12 months)
 * will probably be melted with statistics and econometrics

Raspberry and Arduino series -  I don't know yet how I will proceed, but probably there will be some basic series how to start and then maybe a monthly workshop / experiment video.

All topics will have their own category in blog / youtube, but once in a while I will also post some additional and advanced topics

# Questions and social media engagement

If you have questions - I suggest you write them down in the discussion section under the blogpost. Personally I don’t use Facebook and I am not so much into starting it again. I will try to respond to most questions under the blog, to some under the videos in youtube, but the [Facebook page](https://www.facebook.com/data.science.lt)  will be only used to mirror the new blogposts.

If you have suggestions either what I should cover, or what I could do better, you can always write me an email.

# Support this blog/channel

Right now I offer only the possibility to []“buy me a coffee” using Paypal](https://www.paypal.com/paypalme/lithuanianeconomynet). If this blog / channel attracts enough readers / viewers who want to support this work and make me make more of it - I will create Patreon account later on. The benchmark for this step is:
* having at least 1000 subscribers to my [youtube channel](https://www.youtube.com/channel/UCKDWshSCpVu31ObVq2vI9_g)
* having at least 500 email subscribers for this blog (will be added soon)

I do not monitor with google analytics this webpage, the only trackers that are here, are because I use Disqus for comments, so only the metrics mentioned above are somewhat reliable to me.

![](/assets/2020/08/26/github_cup.jpeg)
