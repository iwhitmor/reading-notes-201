# Local Storage

## Dive Into HTML 5

- **Diving In**

  - Local storage is one of the areas where native client applications have held an advantage over web applications

  - If your local client needs local storage beyond key/value pairs, you can add your own database, invent your own file format, etc

    - Cookies were invented and can be used for small local storage amounts but they have some bad qualities:

    1. Cookies are included with every HTTP request so they can slow down your web app

    2. Cookies are included with every HTTP request so they send a lot of encrypted info over the internet

    3. They are limited to about 4KB of data, not really enough to be useful

  - What we really want in a website:

    - A lot of storage space

    - on the client

    - that persists beyond a page refresh

    - not transmitted over a server

- **HTML5 Storage**

  - A way for web pages to store named key/value pairs locally, withing the web browser. Similar to cookies, this persists after you navigate away from the page. Unlike cookies, this data is never sent to a web server. 

  - From JavaScript you access local storage through the localStorage object on the global window object

  - HTML5 storage is based on named key/value pairs. You store the data based on a named key, then you can retrieve that data with the same key

    - The data is stored as a string

  - A new API has been standardized and implemented across all major browsers, platforms, and devices

  - The Web SQL Database is used by 4 broswers