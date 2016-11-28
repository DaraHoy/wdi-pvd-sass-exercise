# wdi-pvd-sass-exercise
Get familiar with compiling and using Sass

Now that you know the basics of Sass and how it helps you write CSS in a more fun and efficient way, let's master some of those new skills by building on [The Walker](https://github.com/ga-wdi-exercises/the_walker)!

## Sass homework:

- Open up the sass guide: http://sass-lang.com/guide - you will use it later

### Setup:
- From the command line:
 - Go to your The Walker repo from this morning and create a new branch called "sass"

 - Install sass on your computer (using NPM or Ruby - info in the sass guide under "libsass" tab) 
  - this is an intro into package management and the command line - take the time to work through issues and get more familiar with the command line.
 - Write a new file, `style.scss`, and compile that file into `style.css`


### Requirements:
Incorporate these 5 Sass features in your The Walker repo:
 - variables - move common values into variables and use variables to make your code more readable
 - mixins - DRY up your code 
 - nesting: Only apply styles to an element that is within another element (or element with a certain attribute, like class ‘flip’)
 - extends - DRY it up even more
 - importing a partial: create a new file `_walker.scss` that imports into your `style.scss`. 
  - Why use partials?

 - For example, think about “building” the Walker. You have the `<img>` and the `<img>` has certain styles. Imagine you want multiple Walkers, all going different directions and starting at different points. Use Sass to DRY up this logic and get more than one Walker on the page doing their thang.

 - Not sure if it’ll compile? use the sass linter (another program that you can run from the command line)
 - And last: push your The Walker repo and branch to your github account. 

### Bonus: CSS3 Animations
- Check out what’s possible with CSS!
http://codepen.io/una/pen/NxZaNr

- Use CSS3 animations for your walker.
 - Try to make The Walker do all of the previous requirements: starting from the right, switching directions when near the other side of the screen.
 - What functionality can you perform without using JS? Why would you want to use CSS over JS? Why would you stick with JS over CSS?
