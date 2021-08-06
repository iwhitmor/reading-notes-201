# Error Handling & Debugging

## JavaScript - Jon Duckett

- **Chapter 10: Error Handling & Debugging**

  - Everyone makes mistakes when they program. No one can expect to program perfectly every single time. The key is to know how to find the source of mistakes quickly and efficiently so you can keep going when working

  - How to deal with errors

    1: Debug the script to fix errors

    - When you come accross an error while coding, you need to debug the code and track down the source of the error

    2: Handle errors gracefully

    - You can handle errors gracefully using try, catch, throw, and finally statements. Sometimes errors are out of your control and in such cases, it is particularly important to write error-handing code

  - Debugging is about deduction: eliminating potential causes of an error

    - First you need to narrow down the area where the problem seems to be. Once you know where the problem might be, you can then try to find the actual line of code that is causing the error

  - Browser dev tools & JavaScript console

    - The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. The JS console is just one of the several developer tools that are found in all modern browsers
  
  - JS has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error
  
  Information taken from "Javascript & JQuery Interactive Front-End Web Development" by Jon Duckett