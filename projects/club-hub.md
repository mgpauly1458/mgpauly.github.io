---
layout: project
type: project
image: img/club-hub.png
title: "Club Hub"
date: 2023
published: true
labels:
  - Meteor
  - MongoDB
  - Digital Ocean
  - React
summary: "A web application, which allows students at the University of Hawaii to view all the available college clubs and event information."
---

# Club Hub

## Overview

Part of the college experience is participating in extra curricular activities and clubs related to topics that interest you. Our web app is a one stop shop giving students the ability to view every club offering available at UH Manoa. Users can create an account, view and bookmark their favorite clubs, and see all planned club events. Club officers have special privileges and can edit their respective club, and create events for that club.

## Deployment 

This is a link to the live site: [Club Hub (live-site)](https://club-hub.site)

## About Us
### [GitHub Organization Page](https://github.com/mongo-mongoers)

## User Guide

### Club List Page

The Club List page is where you can view all of the clubs that are available at your university. To bookmark a club, click on the "Bookmark" button next to the club's name. Bookmarked clubs will appear in your Bookmarks page. You may also filter clubs by their respective topics.

<img width="1266" alt="image" src="https://user-images.githubusercontent.com/74911365/234210054-98752d0c-4ead-43f5-b401-f524f738a16b.png">

### Bookmarks Page

The Bookmarks page displays all of the clubs that you have bookmarked. To view the events for a bookmarked club, click on the club's name.

<img width="1265" alt="image" src="https://user-images.githubusercontent.com/74911365/234210152-e1136338-9c45-4d16-ab32-e4dfa2bd5ff7.png">

### Events Page

The Events page displays all of the upcoming events for the clubs that you have bookmarked. To view more information about an event, click on the event's title.

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/74911365/234212179-4b6dea97-7499-456c-be88-ddd8dff89a75.png">

### Club Info Page

The Club Info page displays more information about a specific club. This information includes the club's description, meeting times, and contact information.

<img width="1267" alt="image" src="https://user-images.githubusercontent.com/74911365/234210905-d074e690-a898-4533-a28c-c474f83fd700.png">

### Edit Club Page

The Edit Club page allows you to edit the information for a club that you are the officer of. This information includes the club's name, description, meeting times, and contact information.

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/74911365/234210706-6145f99e-e694-4c74-8791-5a3a72bd223f.png">

### Create Events Page (for officers)

The Events page allows officers to create events for the club that they are the officer of. This includes the event's title, date, time, location, and description.

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/74911365/234212417-321b4307-44d7-4771-8790-bcea169cf948.png">

## My Contributions

I worked on the backend of this website and handled the deployment to digital ocean. The front end team members created templates for what the pages are supposed to look like. I created the MongoDB collections, Meteor schemas, server code that connected the page templates to the database. I wrote and tested the 'onHandle' functions for any form being submitted on all the pages. I ensured the database was being manipulated correctly at any given point in the website. I architected a clever way to create many-to-many relations by making a 'joint collection' between other collections. I initialized the database for the team during development, and ensured the deployed app was initialized. I created a digital ocean droplet, and deployed the web app using the 'mup' toolchain. I bought and setup a custom domain and secured our app using SSL encryption.
