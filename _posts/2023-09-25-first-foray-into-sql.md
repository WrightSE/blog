---
layout: post
author:
- Sarah Wright
---

This post marks my first foray into creating SQL schemas using Vertabelo and ERD using LucidChart. Though it isn't necessarily hard to create a database at this point, it is a bit more difficult to read between the lines of the client communication that you're given. The first thing that I created was my ERD, which is displayed below this.

![The LucidChart ERD:]({{ "/assets/images/LucidChartGrocery.PNG" | relative_url }} "LucidChart"){: width="750"}

I'm fairly confident in my organization of the ERD because it only has 3 categories. Attributes are easy to figure out, but entities versus relationships are a bit more difficult. The best sort of rule of thumb for entities/relationships that I have is that the relationships require the existence of at least two entities.

The vertabelo schema was quite a bit more difficult for me because of the sheer number of options available for the data typing. The fact that I had to make an upfront decision on what I thought would be the best representation of the attributes that I had available was difficult and I had a lot of back and forth before I decided on what was the best one for the database I was developing. Eventually, I got pretty settled on what I thought was the best approach to the information that I was given. Below this is the schema I ended up on.

![The Vertabelo Schema:]({{ "/assets/images/VertabeloGrocery.PNG" | relative_url }} "Vertabelo"){: width = "500"}

All in all, SQL simultaneously makes more sense to me while also being a bit more of a pain to plan. Most of this is because of the relationships you have to set up between the tables along with setting the primary key on the tables. It's not that I don't see the usefulness in either of these but rather it just takes sometime for me to sit down and think my way through them at the start rather than making my way through about half the project and then restructuring because I realized I did something wrong. 

