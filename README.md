# Project 0

Web Programming with Python and JavaScript

This is Carlos from "CS50 Web Programing with Python and Javascript" course, and this is project0.

The website is a portfolio website, in which anyone can submit their visual or written portfolio, such as photography, graphic design, paintings or even texts, and it will work as their personal space to share. For the purpose of the project, I have created 4 different profiles, each one of those having as much as 7 different projects inside. Each one has a profile picture, name, email, location, and a static invented number of views.

There are 4 main pages accesible from any place of the site. They are linked through the navigation bar at the top and at the bottom.
They are:
home.html
Submit.html
About_us.html
Users.html

Through the home page, and only through the home page, you can acces the profiles, which are located in the folder named "projects".
Each of the profiles have different projects, and are organized like this.
profile.html
1.html
2.html
3.html
.
.
.

Each projec has a folder in which there are all the files of the projects, right now they are all .jpg files shrunk to a max of 1Mb of space.

Each project page can go back to their mother page profile.html and to all the pages accesible through the navigation bar. Project pages are only accesible through the profile page.

The file web_map.pdf shows how the site is organized.

In the pages accesible from the navigation bar there is a list of names at the bottom of each one, it is a horizontal unordered list and works as a slogan, making the footing of it.
In the page Users.html there is a table of all the profiles with some data so you can see which one of those is more popular based on views (right now is just made up data).
There are many images in the website since it is it's purpose, to host images.

The whole website is based on bootstrap and its grid scheme. It is fully responsible even for the smalles of the smartphones, with navigation bar options that stack on top of each other and even the main logo of the website becoming smaller as the screen does.

The page that remained the biggest challenge to make responsive was profile.html in each of the profiles. This page has a card on the left with the profile information, and on the right, one on top of each other each of the projects. As you make the width smaller, the card of the profile stacks itself on top of the projects so you can see them in a single column, and it rearranges all the info inside the card so it looks good.

I have made every one of the links to the profiles and the projects responsive to hover. It makes the opacity of the picture fade and the name of the project/profile appear. This is so you can choose what to visit based on visual experience and not conditioned on the name of the artist or the project.

All the info of the profiles are variables in the sass file, so you can change the name or the location of any of those, and it will change through all the different pages that it appears.
In the sass file there is also nesting to make the hover code easyer to write. And some inheritance, not because I really neded it, but to fulfill the requirements of the project.

The file video.html is the one that links to the youtube video explanation. There is no access to it from any other page, but beacuse it is not a part of the website.







