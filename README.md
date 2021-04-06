# Latin Blog

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Live website](#live-website)

## General info
This project is a simple blog app.

The content for each blog is retrieved from the [JSON placeholder API](https://jsonplaceholder.typicode.com) through the initialisation of an Axios instance.

In addition, you also have the opportunity of adding your own 'blog' to the DOM. This can be found when clicking on the "New Post" navigational link. All code related to this section (New Post) of the Latin Blog app are loaded lazily.
The implementation of lazy loading within this project is nonsensical considering its build size. Nonetheless, it has been added to show knowledge of its purpose. 
Disclaimer: React.Suspense has not been implemented to tackle lazy loading within this project because it has only been made available from React version 16.6 onwards. Also due to it being within the [experimental stage](https://reactjs.org/docs/concurrent-mode-suspense.html).

Components in this project are class-based.

Moreover, the core purpose of project Latin Blog is to showcase my implementation of React Router DOM to create a Single Page Application (SPA).
	
## Technologies
Latin Blog is created using:
* react version: 16.0
* react-router-dom version: 5.2.0
* axios version: 0.16.2

## Live website
The link for a live demonstration of how this app works can be found here; 
[Latin Blog](https://commit-kyle.github.io/latin_blog/)

I hope you've enjoyed it!
