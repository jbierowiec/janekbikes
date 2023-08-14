# escnyc.com

## Welcome to my blog!

This blog is about my travels in and around NYC that give a feeling of leaving the stresses of city life for a day or two. More of my goals with the blog are explained in my first blog post. If you would like to check out the blog, click the link down below:

[escnyc.com](https://escnyc.com)

This website uses HTML, CSS, Nunjucks, eleventy.js, and Netlify's Content Management System (CMS) which was also used as the Static Site Generator for the website. The `src` folder contains all the files that are the bulk of the site. The folder contains:

* The Nunjucks files are used as a base for creating page layouts and templates for how the blog is structured.
  - They create page layouts on the website by having default settings of where the header, content, and footer should be located on the page for example
  - They create templates for the blog posts by set requirements of what a blog should have, for example: a title, description, image, image caption, content, posted or featured, and if it should be published or not.
* The CSS files is used for styling the pages
* 3 blog articles for now all in the `blog`, two of which have been written in the admin panel and one hardcoded
* images and the logo for the blog posts are in the `assets` folder
* The `public` folder contains the backend for the website, where all the formatting of the blog posts is contained
