# Interactive Frontend Development Milestone Project
Built by **_Cecilia Barriga_**

This is a Single-Page Application (SPA), that calls on the Google Maps API and the Google Places API to allow users to search for information about any city they are planning to travel to. 

## UX
This website is intended for people who are are searching for all the information needed of the city they are planning to visit next. They are able to:
Select a city
Find tourist attractions
Find accommodation
Find bars, restaurants and coffee shops

I wanted to show images of different cities in the index page with a simple CTA, and then open a modal with the google maps search.

## Features
I wanted to show images of different cities in the index page with a simple CTA button that when hovered the font becomes lightgray and has a pointer.
Once the button is clicked then open the Google Maps modal;

In this modal, On the top-left side the user can type the city they are looking for in an input;
On the top-right side there is a drop-down with the different locations: hotels, bars, restaurant, coffee shops, museums and parks. Once an option is selected, icons will drop on the map according the selection.
If this icon is clicked, there will be a info window displayed with the name of the establishment and its information.

All the links from the Info Window will open in a new tab as the attribute target="_blank" was used.


## Technologies Used
* HTML5 
* CSS3 
* JavaScript 
* Maps JavaScript API 
* Cloud9 IDE
* GitHub 


## Testing
This site was tested in google dev tools including responsiveness on mobile devices and tablets, to make sure everything was working and that everything was shown the way it is supposed to be seen.

According to https://varvy.com/mobile/ the website scored 100/100 on being mobile friendly.

Site was tested on the following browsers:
* Google Chrome
* Mozilla Firefox

I tested the modal by opening and close it, to make sure it works.
In the map modal I typed the city and selected from the deployed list by clicking it and also with the arrows and then enter to make sure both ways would work.
I made sure all the locations (hotels, bars...) were working even if I changed a city.

I did have a bug, which was when I typed a city no cities were deployed from the list, and I could not select any. It is now fixed, and my mentor helped me to fixed this. He realize that the modal-backdrop was on the top of it so using z-index we were able to bring the pac-container up.

## Deployment
I created a repository on GitHub and through commits using Cloud9 terminal I added the content with the following commands:
- git add FILE NAME
- git commit -m ""
- git push https://github.com/cesole/google-api-project

I used HTML and CSS validator, and also JSHint for JavaScript to make sure there were no issues.

I used Figma to create the wireframe.

## Content
Most of the JavaScript has been taken from the Google Maps JavaScript API Documentation.
The icons were taken from https://mapicons.mapsmarker.com/.


## Acknowledgements
Google Maps Platform Documentation
Code Institute tutors
Code Institute Mentor