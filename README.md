# React Assignment

### General rules and requirements

* Use any npm package you find appropriate.
* Ask questions when in doubt what we expect.
* When you are not able to solve something in reasonable amount of time, write an explanation of why
  (what knowledge is missing, why it needs so much time, etc.).
* Write a Readme file with all information required to run in locally + all additional information you find worthy to share.
* Where we don't ask for any specific tool/coding approach, use any according to your preferences.
  You may write a brief explanation of your choice.
* Follow all code quality principles you know and are used to.
* You should not spend with our assignment more than 6 hours.
  When this is not doable, choose what to implement and what not to.
* Send us your work preferably as a link to git repository (e.g. GitHub).


### Time for finishing
* First read the assigment and make clear you understand what we ask for.
* Try to estimate the time you require to finish it.
* Email us your estimation and a date, where you expect to be done.
  Aim for realistic date and keep in mind all other responsibilities you may have
  (your current work, family duties, vacation or public holidays)


## App description
We are going to ask you for just another ToDo list app.
The app have only one page showing list of all todos as you may see on following wireframe.

![](wireframes.jpg)

### Functional requirements:
1. You may add a new todo item using the form on the top.
2. Items are sorted. Rules are: first open, then closed. Open items are then sorted alphabetically.
Closed items are sorted by date, most recently closed are first.
3. Clicking a checkbox of an open item marks it done.
Checkbox and text appearance changes and the item moves from open items into closed.
4. Clicking a checkbox of closed item reopen it again.
5. On mouse hover, a remove icon appears (see "Lorem ipsum dolor" item). Clicking on the icon removes the item.
6. Changes in items should be persistent between browser refresh (more robust persistence is not required).
7. Open item can be edited by clicking on its text. Reuse the form for creating new items. Closed items can't be edited.

As an API feel free to use [json-server](https://github.com/typicode/json-server) npm package (either locally or as a [service](https://jsonplaceholder.typicode.com)) or any similar solution.
But definitely do use some API service. It doesn't matter whether the API runs remotely or locally.

### Non-functional requirements
1. Use functional components and not class based components.
2. Use react hooks where appropriate.
1. Use TypeScript.
1. (optional, but preferred) Write tests using your favorite testing tool.
100% code coverage is not required, but having few meaningful tests would be fine.


### Additional tasks
These tasks are kind of optional. But please try to finish as much of them as you can.
When we ask to use some approach, design pattern or tool you are not familiar with, we encourage you to give it a try.
We will really appreciate when you try to use something new to you in this assignment.

1. Implement Higher Order Component (HOC) `withLogging`. Any wrapped component logs its mounts, unmounts and renders to console.
Use it at least for components representing a todo item.
1. Use async/await for at least one method calling API.
1. Use Redux-Toolkit instead of pure Redux

The goal here obviously isn't to improve the todo app but to better check your React knowledge.
