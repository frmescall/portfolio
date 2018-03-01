# Static Boilerplate Code by cmdmescall

## Project Info

Currently this is just a blank template I created for building any static site. It uses PostCSS, CSSNano, BrowserSync and Gulp so that you can build in a modular fashion and have it auto-update as you code.

If you find this, you're free to use it.

Delete all of this text and add your information here about the project you're working on.

## Build & development

- Make sure you have NPM installed on your machine
- Clone the repo to your local drive using `git clone https://github.com/cmdmescall/site-boilerplate.git`
- In the command line run `git remote rm origin` to remove this repo as the origin, then run `git remote add origin https://github.com/YOUR-USER/YOUR-REPO.git` to migrate it to your own. Then the usual `git add .`, `git commit -m 'first'`, `git push origin master`
- run `npm install` to install the dev dependencies (such as PostCSS, Gulp etc)
- then run `gulp watch` to initiate gulp. This will load up the `index.html` page in your browser
- `gulp watch` can sit in the background whilst you build the site, you don't need to do anything else
- Once this is done use the `temp\modules` folder for creating css files for your page. Use @include to include them in the `temp\styles\styles.css`
- Each time you save index.html or any css files it will auto-refresh the browser. If it doesn't do this then check your console for errors
- To exit the Gulp Watch task press `ctrl + c` (or the Mac equivalent) or just close the console

## Future Updates

Once I get my head around Webpack I intend to update this so it will also auto-compile any .js files. The structure is there, I just need to get better.