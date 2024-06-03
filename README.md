# csharp-todo-list-command-line-app

My solution to **Boolean UK**'s csharp-workshop-challenge to build a to-do list app in C#.

The challenge required the app to allow for tasks to be added and deleted, and for a completion status to be displayed, with a toggle option.
Optional requirements included a Todo Item class, and the implementation of a unique identifier.

## app features

* displays menu options
* listens for user input
* can be exited with `ctrl + C` or `exit` + `enter`
* to-do tasks have unique identifiers
* to-do tasks can be added
* to-do tasks can be deleted
* attemps to delete an inexistent task results in an appropriate message
* to-do tasks completion status can be toggled
* attemps to toggle the completion status on an inexistent task results in an appropriate message
* when a change is made to the list of to-dos, the updated list is logged onto the console.

## Personal learning aims

* Use correct C# syntax
* Familiarise myself with Visual Studio Community
* Write a .Net command line application
* Implement a linked list data structure
* Implement dependency injection (in this case, TodoList into TodoItem)

## Manually testing the app with Git bash or similar

* `git clone` this repo
* navigate into `csharp-todo-list-command-line-app/Todo-Challenge/Todo-Challenge`
* `dotnet run .`
* keep an eye out for the menu options
* try out the various options (1 - add, 2 - delete, 3 - toggle completion status)
* `ctrl + C` or `exit` + `enter` to stop running the app

Any feedback welcome!
