Coding Challenge for iOS
====================================

Overview
----------------

Your goal is to build a simple iPad app for creating floor layouts using a 'drag and drop' interface and visual furniture elements. The app must be able to persist each floor layout created and also provide a way to browse all previously created floor layouts. A basic functional spec and some guidelines are provided below, but you are welcome to get as creative as you wish. This is a simple project, but organize, design, test and document your code as if it were going into production. Please then send us a link to the hosted repository (e.g. Github/Bitbucket).

Write your README as if it was for a production service, and include the following items:

* An overview of how your code is organized and how the various components interact with each other. Include descriptions of the functionality of each model, view, controller etc.
* Technical design decisions made by you (E.g. What made you choose a particular database, data structure, algorithm etc.)
* Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project
* Any third-party libraries or code snippets you might have used.
* Minimum requirements for bulding and running your code (E.g. iOS version etc.)


Functional Spec
-------------------

* A 'drag and drop' interface is required. The User must be able to pick from at least 3 different furniture elements and place the elements on a part of the screen representing the floor.
* Any number of furniture elements can be placed on a floor in a single layout as long as the elements do not overlap.
* Each furniture element in a layout should have a text field to give it a name.
* Each layout should have a text field to give it a name
* 'New' button to create a fresh (empty) layout. Pressing 'New' should discard the layout currently on the screen (unless it has been explicitly saved)
* 'Save' button to save the layout that is currently on the screen.
* 'Browse' button to present the user with a list of previosuly saved layouts. Clicking on the name of a previously saved layout should display it in the same area used for creating layouts.
* Furniture elements placed on a layout can be moved around further, until the 'Save' button is pressed. Once a layout is saved, it cannot be edited.
* The saved layouts must persist between app re-starts.


Guidelines
---------------

* We have provided some wireframes below to give you an idea of what we expect the app might look like.
* Dont focus too much on creating a pixel-perfect UI. It should just be neat and easy to operate.
* How you choose to persist the floor layouts is pretty open-ended.






