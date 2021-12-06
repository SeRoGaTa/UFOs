# UFOs

***Version 1.0.0***

---

## Overview of Project
#### This report has the objective to create a web page that has information from UFO's, giving a dataset to work with, it has several UFO cases that we will use to create a a table inside the webpage that has some filters so we can manage the information easier.

#### This webpage construction has two parts.

1. The looks and feel of the page which is basically the orientation and localization of the information as well as the formatting of the same, here we can see we change the default colors, pictures of backgrounds and different letter sizes and types.
2. The information show, here we first shown the complete data into a table, but we also offer to the user the ability to filter by some fields the table is shown and with each field the user choose, the table gets updated

## Results

#### As a result, you can see how this webpage end it up and how you can interact with it, here we are using 3 main files:

1. index.html
2. data.js
3. app.js

#### From these 3 files we jump between them to grab, filter and then shown all the information in the webpage. As a side learning path, we use the forEach method to iterate from several items of an object as well as the filter method to show only what is requested.

#### Once you add data into a any text box, the code will automatically detects any change and grab the value you input to then save it into an object which later will be iterated to get the values and filter every row of the complete data set.

#### Here is the main filter which will iterate thru all the values of the object an then filter the table.

<img src="https://github.com/SeRoGaTa/UFOs/blob/main/images/webpage.png" width="300"> 

#### This is an image of the web page

<img src="https://github.com/SeRoGaTa/UFOs/blob/main/images/webpage.png" width="1150"> 

## Summary
#### As summary on this project we learn a lot of different topics as:

- Use of javaScript to build a web page.
- Use of methods to iterate and filter between object items.
- Use and call of functions and variables.
- The basic construction and formatting of a webpage in html.

#### The problem with this webpage is that you need maybe more filters to really get what you want but also, add the ability to choose which filters to apply. Other way could be that you might add the filters directly to the top of the table to visually located them in the table easyer.

#### Something else we could further develop are the following:

- Add a word search for the comments, with this we could search for an specific word to retrieve the data.
- Add some extract button to get the table and save it into a local file.
- 
#### With this module I can say this will be very useful in the future when we want to show ours results from different types of analysis.

#### You can locate the complete js and css files used in [Static Folder](https://github.com/SeRoGaTa/UFOs/tree/main/static) and all images used in the following folder [Images Folder](https://github.com/SeRoGaTa/UFOs/tree/main/images)
