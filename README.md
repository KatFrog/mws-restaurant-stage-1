# Restaurant Review App

This is the fifth project I completed for the Front-End Web Development Nanodegree.  Udacity provided the base code for a barely functioning website, and required that each student:
- Make the provided website fully responsive,
- Make the website available offline using a service worker and caching, and
- Make the site accessible (ARIA compliant).

## Decisions, Decisions, Decisions
To complete this project, I needed to make several decisions.  In no particular order, I decided the following:
-  The base code included functions for implementing this app using either Leaflet or Google Maps. I chose to use Leaflet, so I removed the Google Maps code from the files to help with maintainability.
- I added a polyfill for service worker for cases where a user is running the app on an older browser.
- Even though this is a class project and all of the images currently being used are here, I added an "Image Not Available" image to make the code more expandable and dynamic.
- I created a simple function to add the alt tag to images instead of adding the alt tag directly in the code because I believe the parallelism will make maintainability easier.
