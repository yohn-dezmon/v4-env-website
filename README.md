# Website for Bushwick Eco Initiatives (V4)

This project uses bootstrap, hugo, markdown, html, and css.

The homepage is at layouts/index.html.  
The about page is at content/about.md.  
The rest of the content pages are in content/ and are in markdown.
The files that are in the themes/hugo-tanka folder will be used by default unless
you overwrite them with files in the root level folder.


### theme: hugo-tanka --> https://themes.gohugo.io/themes/hugo-tanka/

### Commands issued:

Creating project skeleton:  
`hugo new site v3-env-website`

Starting up git:  
`git init`

Adding a theme:  
(from root) `git submodule add https://github.com/nanxstats/hugo-tanka.git themes/hugo-tanka`

Creating Content:  
`hugo new posts/my-first-post.md`  
`hugo new about/bushwick-eco-about.md`

Starting server:  
`hugo server -D`

How to use markdown with hugo:  
https://www.markdownguide.org/tools/hugo/

### Deploying with Netlify

https://gohugo.io/hosting-and-deployment/hosting-on-netlify/


## Questions:

1. How do I track how many times a link has been clicked?
- for now I can just link to linktr.ee though that's kind of annoying for users...
