# Un.titled Front End Developer test project

## Objectives

- Recreate [this](https://projects.invisionapp.com/share/CXV79L5S29U#/screens/397139710) design
- Clone this repo, and when you've finished zip it up and email to [harry.edwards@un.titled.co.uk](harry.edwards@un.titled.co.uk) (please leave all working files, but feel free to remove `node_modules` if you have it!)

## Spec

- The header should be sticky
- The header, banner image & footer should be full bleed
- Other content should have a max column width of 1500px
- Links don't need to go anywhere/you can provide example markup
- The map overlay should be triggered when clicking on the `View map` button

## Assets

- Images/icons are stored in the `assets` folder
- Fonts can be found [here](https://fonts.google.com/specimen/Poppins)
- Map embed code:

```html
<iframe
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1615.9254597722654!2d-1.1339286902650432!3d52.63915745447631!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb7314784b68c14c0!2sUn.titled!5e0!3m2!1sen!2suk!4v1575994684235!5m2!1sen!2suk"
  width="600"
  height="450"
  frameborder="0"
  style="border:0;"
  allowfullscreen=""
></iframe>
```

## Technology

- Use whatever technology you feel comfortable with (recommended `scss`/`sass`, `ES6`, `Gulp`/`Webpack`)
- The page must be responsive (at a minumum small mobile screens & average laptop sized screens)
- Minumum browser requirements are Edge, Chrome (latest), Firefox (latest)

### Hints

- Think of this page as being part of a larger site, so your code should be reusable where logical
- Use common best practices wherever possible
- Keep accessibility in mind
- Make the page as performant as you can
- SEO is very important
- Comments are great for telling us what you're thinking

#### Legal

- The assets & design included in this repo are to only be used for the purposes of this exercice and may not be used in any form for other projects without prior written consent. The code you write is yours to do with as you please.

### for setup of compiler of css from scss

<!-- run on terminal -->

Run "npm init" for installing project dependencies using npm then run "npm install -g gulp-cli" for installing gulp globally by npm then run "npm install gulp" for installing gulp using npm then run "npm install sass gulp gulp-sass" this is used to install the necessary dependencies for compiling Sass (SCSS) to CSS using Gulp. Then run "npm install gulp-uglifycss and gulp-concat" for installing the dependencies. Then we need to create a file name "gulpfile.js" where we have to write the code for the compilation.
Then we can rul "gulp" and it will compole our files into minified versions. 
