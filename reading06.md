# Problem Domain, Objects, and the DOM

## Problem Domain

- Understanding the problem domain is the hardest part of programming

- Problem domains are hard because it is very difficult to solve a problem before you know the question

- 2 things you can do:

  - Make the problem domain easier

  - Get better at understanding the problem domain

## JavaScript - Jon Duckett

- **Chapter 3: Object Literals**

  - Objects group together a set of variables and functions to create a model

  - In an object: variables become known as properties

  - In an object: functions become known as methods

  - Example below: This object represents a hotel

    - var Hotel = {
      name: 'Quay'.
      rooms: 40,
      booked: 25,
      gym: true,
      roomTypes: ['twin', 'double', 'suite'],
      checkAvailability: function() {
        return this.rooms - this.booked;
        }
      }

    - Name, rooms, booked, gym, roomTypes are PROPERTIES

    - checkAvailability is the METHOD

- **Chapter 5: Document Object Model**

  - DOM specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window

  - DOM is neither part of HTML nor part of JavaScript; it is a separate set of rules.

  - It is implemated by all browser makers and covers two areas:

    - Making a model of the HTML page

    - Accessing and changing the HTML page

    - DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes

    - You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax

    - Browsers off tools for viewing the DOM tree

All information taken from "Javascript & JQuery Interactive Front-End Web Development" by Jon Duckett and the web article [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
