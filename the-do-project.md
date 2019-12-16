# The Do Project

*The Do Project* defines a standard syntax for creating plain text do lists.

This is a formal write-up of the syntax that I use for all my plain text do lists. I mostly use plain text do lists because I find them to fit well with the work I do. They are well suited for small programming projects and generally any kind of task that needs to get done on your computer.

Let's start with an example of a simple do list; I will explain the syntax below.
```
2019-10-7 Monday
- publish first draft for the do project
x write first draft for the do project
! polish first draft for the do project

Backlog
- create a page for the do project

Wishlist
- create a compiler, do to html
```
From the example we see that the do list is divided into sections. A *section* is any block of text with an empty line above and below it; so basically a paragraph. Headings are a simple text to let you know what the coming section is about, when it's due, etc. A *heading* is simply the first line of text in a section.

Each section contains a number of tasks which can be in one of three states.
- `-` **Do**: something to get done.  
- `x` **Done**: something that got done.  
- `!` **Cancelled**: something that had to get done but did not get done.
  

You can save your do lists with whatever extension you want. `.txt` and `.md` are good options and you can even use the `.do` extension if you want to be cool. `--filename.txt` is the syntax I use for my do files. Let me dissect the syntax of an example do file to make it more understandable.
```
--2019-October.txt
```
The first character in a file name represents its state (in this case *do*), all following characters have no special meaning. If the list is completed or cancelled we change the first character to reflect the change of state.
```
x-2019-October.txt
```
```
!-2019-October.txt
```
This helps makes folders with a lot of different do lists easier to manage as you can groups files by their state (do, done, cancelled).


### That's it! I hope this helps you keep track of what you need to do.