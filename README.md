# Bodhi Services Website

### How to run the website locally

* Clone this repo
* Open in Rstudio (click on .rproj file)
* Install blogdown package in Rstudio
* run blogdown::build_site()
* run blogdown::serve_site()

### Pushing to this repo

Whenever you push to this repo, it will trigger a wercker process which will rebuild the /public file and copy it to /var/www/html on the server and recr

### Adding a new blog post

blogdown::newpost() update the R markdown file, push to git, and the new blog post will appear on the website.

### Updating Other website elements

more info coming