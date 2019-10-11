# The do Project

The do Project defines a standard syntax for creating plain text *do lists* (like a to do list but with less postponing and more getting things done). 

## Syntax of a *do list*
Let's start with an example of a simple do list; I will explain the syntax below.
```
2019.10.07 Monday
- polish first draft for the do project
x write first draft for the do project
! don't update windows

Backlog
- create website for the do project
- test out the do project in real life

Wishlist
- create a compiler, do to html
```
### Sections
- **Section**: any block of text with an empty line above and below it, much like a paragraph. Used to group similar tasks. Note: for the first and last sections there is no need for an empty line above and respectively below them.
- **Section Heading**: the first line in a section, should be a simple text to let you know what the section is about. In the above example `2019.10.07 Monday`, `Backlog` and `Wishlist` are section headings.
  
### States
A task can be in one of three states.
- `-` **Do**: something to get done.  
- `x` **Done**: something that got done.  
- `!` **Cancelled**: something that had to get done but did not get done.

## Syntax of a *do file*

`.do` is the official file extension for a do list because I said so. The basic syntax for a do file is `--filename.do` but let's dissect the syntax of an example do file to make it more understandable.
```
--2019-October.do
```
Now it gets a little confusing. The first character in a file name represents its state (in this case *do*) but all following dashes are used instead of a space and have no special meaning. If the list is completed or cancelled we change the first character to reflect the change of state.
```
x-2019-October.do
```
```
!-2019-October.do
```
This helps makes folders with a lot of different do lists easier to manage as it groups files by their state (do, done, cancelled).


### That's it! With three characters and a little formatting knowledge you are ready to get productive.