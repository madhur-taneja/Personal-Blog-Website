# Personal Blog Website

A multi-page website built using `HTML` and `CSS` skills which includes custom images, layout, and styling. Along with the webpage design considerations, I worked to appropriately structure the files, as well as use proper formatting & style. The project also focusses on using Flexbox and Grid systems to make the page responsive.

Open and view the Project using the `.zip` file provided or at my [Github Repository](https://github.com/madhur-taneja/Personal-Blog-Website).

The project is also hosted on [Github](https://madhur-taneja.github.io/Personal-Blog-Website).

## Table of Contents
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
- [Development](#development)
- [Features](#features)
- [Running the App](#running-the-app)
- [References](#references)

## Getting Started

This project was built from scratch and is a part of Udacity's Refreshed Front-End Nanodegree program. 

The project will be evaluated by a Udacity code reviewer according to the Personal Blog Website project [rubric](https://review.udacity.com/#!/rubrics/2667/view)

### Tools Required

No additional tools are required apart from a text editor of your choice

### Installation

No additional installation is required for this project

## Development

* Create `index.html` as the landing page with the following:
  * Navbar with links to other pages
  * Cover image 
  * Basic page content
  * Footer with social media links
  
* Create `views` directory with the following pages:
  * `AboutUsComponent.html` with about-us info
  * `BlogsComponent.html` with all blog posts
  * `BlogPostComponent.html` about one of the post
  
  Reuse navbar and footer code

* Create `css` directory with the following files:
  * `styles.css` with the global styling
  
  Page Specific CSS
  * `aboutus.css`
  * `blogpost.css`
  * `blogs.css`
  
  Component specific CSS
  * `footer.css`
  * `navbar.css`

  Import all the modularized css files to `css/styles.css`

* Create `js` directory with the following file:
  * `app.js` for adding navbar toggle button functionality

For details now how everything has been implemented, refer the source code.

## Features

* Only first blog post has a dedicated page for it, rest are all dummies.
* Flexbox and Grid are used for all pages.
* There are 2 major pages for the website: `Landing page` and `Blogs Homepage`
* The project also contains a dedicated `About-Us` page.

## Running the App

* Open the project through the `.zip` file provided and extract the files. 
  > Open `index.html` in the browser of your choice.

## References

* Responsive navbar from [itnext](https://itnext.io/how-to-build-a-responsive-navbar-using-flexbox-and-javascript-eb0af24f19bf)
* Images used from [Pixabay](https://pixabay.com/) 
* Blog Content from [The Nomadic Matt](https://www.nomadicmatt.com/)
