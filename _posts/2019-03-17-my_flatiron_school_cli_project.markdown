---
layout: post
title:      "My Flatiron School CLI Project"
date:       2019-03-17 22:16:10 +0000
permalink:  my_flatiron_school_cli_project
---


**The Gem**
	
I completed my CLI project, a Ruby gem designed to give the user information about camping options in Joshua Tree National Park, one of the most beautiful places I have ever camped. The gem scrapes the National Park Service webpage (nps.gov) for the names of the available campgrounds, as well as basic information about each campground including number of sites, price per night, elevation, and basic amenities such as water and bathrooms.

![Joshua Trees in Joshua Tree National Park](https://res.cloudinary.com/karlymareka/image/upload/c_scale,w_695/v1552858419/IMG_3321_copy.jpg)
 
The information is scraped once and saved in the JoshuaTree::Campground class. Each campground is saved, along with its information, as an instance of the class. The gem then outputs to the user a list of the campground names, and the user types in the name of a campground to see more information. The gem retrieves the instance of the class and outputs to the user the campground information. After viewing the information, the user can choose to quit the program or go back to the menu of campgrounds to choose another campground.

![screenshot of CLI project in terminal](https://res.cloudinary.com/karlymareka/image/upload/c_scale,w_695/v1552857303/Screen_Shot_2019-03-17_at_1.26.21_PM.png)

**The Process**

The biggest challenge I faced creating this gem was deciding which parts of the code belonged in the JoshuaTree::CLI class and which parts belonged in the JoshuaTree::Campground class. My first instinct as a beginner was to just put everything in the CLI class, which made it too long, complex, and difficult to read. I believed my project was improved by simplifying the CLI class, as well as creating more methods within that class, each of which accomplished only one task. 

The easiest part of the process was actually the part I initially feared—the actual scraping. Fortunately, the website I chose to scrape was very scrapable, and the code was simple and organized, making this part of the process a breeze. Another roadblock I hit early on in the project was trouble with the in-browser IDE. Once I switched to a local environment, things went much more smoothly. I would still like to use the in-browser IDE for labs, but for the next project I will definitely use my local environment from the start.

**What I Learned**
	
I read some other Flatiron School blog posts about the CLI project and noticed that many people said they wish they had planned and prepared more before just diving in. Interestingly, I felt the opposite. Maybe it just depends on your personality. But I tend to be an over-preparer, and sometimes I have trouble diving into something new if I don’t feel fully ready. The thing is, for me learning to code is about surrounding myself with the unknown and unfamiliar over and over, and just learning to get comfortable wading through the murky mess until I can make sense of it. For me, I need to stop overthinking things sometimes and just dive into something new!  

![The trail we blaze!](http://www.skolliekampe.org.za/skollie/wp-content/uploads/2016/01/the-trail-that-we-blaze.gif)

