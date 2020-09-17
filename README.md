# Wordpress-dev-env
When I was developing a wordpress theme using _s ([Underscore](https://underscores.me/)), I need: 

1. auto compiling `.scss` to `.css` on save, 
1. auto refreshing browser. Here stores some key files.

The files mainly come from a course on Lynda.com (the course is deprecated. I searched it out on google) which is about _s.


[WordPress: Building Themes from Scratch Using Underscores](https://www.lynda.com/WordPress-tutorials/WordPress-Building-Themes-from-Scratch-Using-Underscores/491704-2.html)
by Morten Rand-Hendriksen [@mor10](https://github.com/mor10)

But the packages are quite old. While running in Sep, 2020, meets so many inconsistancy and vulnerabilities.

I don't know where to find new ways to meet my needs, so I tried to repair it.

It works just fine.

## Usage

#### Make sure you have installed Node.js.

1. Under 'themes' folder of Wordpress site, create a new folder, name it what ever you want, by convention, I name it 'gulp-dev'.
1. Put `Gulpfile.js` and `package.json` into the folder.
1. Change placeholders near `line 1` and `line 68` of  `Gulpfile.js` 
1. Go to the folder in terminal.
1. `npm install`
1. `gulp`
