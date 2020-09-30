## Connoisseur: Free Website Template

Connoisseur is a **bold** and **modern** website template suitable for websites pertaining to fine arts, cuisines, dining etc. It is **cross browser compatible** made using **HTML5** and **CSS3** with
inbuilt **web font**, necessary **jQuery plugins**and much more. You are free to use it for your personal as well as commercial projects. It is released under **New BSD License**, read more about it at
http://www.opensource.org/licenses/bsd-license.php.

**Release Page
at http://priteshgupta.com/templates/connoisseur/**

### Customizing Individual Pages

-   Open the respective html files within the folder “Connoisseur” using
    any WYSIWYG or text editor. 
-   Replace the default text and the default links.
-   Featured Slider should contain images of ratio 24:10.
-   Featured Images should also contain images of ratio 24:10. 
-   No lightbox has been set for images for any page other than the
    “**Gallery**” page, to enable lightbox for images on other pages,
    simply follow the instructions at http://fancybox.net/howto.
-   All pages are by default with sidebar(except “**Gallery**” and
    **Home**”), to make any particular page full width, make sure that
    you have removed the \<aside\> section entirely and add the class
    “fullwidth” to the element article, that is, \<article\> should
    become \<article class=”fullwidth”\>.

## Getting Started

  * Copy `settings.sample.js` to `settings.js` and populate the fields in it  // TODO: create a CLI tool to handle this
  * `npm install` to download all the dependencies
  * `npm run db:setup` will set up the database and table in RethinkDB
  * `npm run server` will start the Node server in development mode
  * `npm run client` will start `webpack-dev-server` for the frontend of the project on port 8050, which will proxy the backend.
  * `npm run build` will build the frontend for production
  * `npm start` will start the server in production mode  // TODO: production mode needs more work and testing
  * `npm run clean` will delete the production files that webpack builds

## Typography

The website is using “Lobster” font for headers. The other font being used is “Century Gothic”. 
