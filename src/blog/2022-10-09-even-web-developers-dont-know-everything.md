---
title: Even Web Developers don't Know Everything
author: Jean Schleppy
description: In this article, I go over a tip by Michelle Barker about how it's
  ok to acknowledge the fact that you don't know everything.
date: 2022-10-09T03:52:47.290Z
tags:
  - post
image: /assets/blog/computer-clement-helardot.jpg
imageAlt: Open Computer with code editor open
---
During the course of my Web Development 2 class, I have recently learned that it is ok to not know everything. I am surprised that even professional web developers can admit when they do not know a certain subject because when I was getting my bachelor's degree, I was told by many professors that I will need to know everything I learned in class. After taking Web Development 1 and going through the modules of Web Development 2, I am learning that it is ok to say I don't know and look up answers to make sure that I can assist others in the future.

One instance where I encountered something I did not know was when I had to deploy my poem site to Netlify. In the assignment, I had to take the webpage I created with the poem, (“*Hope is the Thing with Feathers”* by *Emily Dickinson*) and deploy it to Netlify so that it could be viewable to the public. I only had familiar knowledge with CSS and HTML, so I went and edited the code in the CSS file.

![Main.Css File]("/Users/jschl/Pictures/Saved Pictures/CSS-Poem-Page.png" "Main.CSS file")

However, the problem I came across was when I tried to commit my changes to GitHub. Since the main.css file was under the public folder, it was not able to push the changes to GitHub, because GitHub was looking for changes made under the src folder.

![Src Folder]("/Users/jschl/Pictures/Saved Pictures/Poem-Page-src.png" "Src Folder")

Because I could not figure out why my changes would not get committed to GitHub, I created extra work for myself by creating another main.css file in the src folder so that my changes would get committed.

My next mistake was deploying the actual webpage to Netlify, a platform that takes GitHub repositories and turns them into a public website for everyone to view. The directions in the assignment said that the site should be looking at the public folder when deploying the webpage. However, because I created that extra work for myself, when I deployed the web page, it looked completely different than what I was seeing on my local browser. It took me awhile, but I was able to read the directions again and figure out where I went wrong.

My time spent working on this project was stressful because I was being hard on myself and saying I should know where the problem is and how to fix it. If I had known ahead of time that it is ok to not know all the answers, it would have changed the way I approached this assignment. This tip from Michelle Barker is one I want to personally remember because I often find myself getting stressed out whenever I do not know how to solve the problem, and I feel that I am not alone. As Michelle Barker said “No-one knows *everything* about a topic (with a few exceptions!). You don’t have to be an expert at something to write a useful article about it”.

In conclusion, I believe that it is very useful for beginner web developers to say when they don’t know the answer to a certain topic. This is important because the ones that say they do not know the answer to a topic will have their questions answered. Eventually, they will gain enough knowledge to help others by sharing the information they have learned along the way.

Resources:

Link: <https://css-irl.info/tips-for-writing-for-the-web/>

I﻿mage Credit: *Clement Helardot*