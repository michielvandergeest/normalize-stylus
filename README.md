# Stylus version of Normalize.css

## Why?

I love using *[Stylus](http://stylus-lang.com/ "Stylus")* as my dynamic CSS language and
*[Normalize.css](https://necolas.github.io/normalize.css/ "Normalize.css")* is my go to library for resetting CSS styles.

The problem: *Normalize.css* is written in pure CSS, which doesn't work too well to import into a *Stylus* project.

Most of the time I would end up copy-pasting *Normalize.css*'s CSS into my project. Not ideal!

That's why I've created this simple repository that converts the latest version of *Normalize.css* to a *Stylus* file,
which can then be easily imported via *NPM* into the working project.

 ## Installation

 Install using NPM

 ```
 npm install normalize-stylus --save
 ```

 ## How to use it

 After installing, a file ```normalize.styl``` will be created in the ```node_modules/normalize-stylus```-folder.

All you have to do is add the following snippet to your stylus file, and you're ready to start using *Normalize.css*!

```
@import 'normalize-stylus'
```

## Acknowledgements

Normalize.css is written by [Nicolas Gallagher](https://github.com/necolas, "Nicolas Gallagher").
