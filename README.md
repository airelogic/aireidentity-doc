# AireIdentity Docs

This project holds the online knowledge base for people wishing to learn to use AireIdentity as a tenant admin/admin. The project contains both the Jekyll template files as well as the specific help content.

## Adding / editing new content

Most of the content you are likely to edit will be either in the _docs or _posts folders. In general _docs is for static content, whilst _posts is more for blog/news. If you want to create some draft content that you would like backed up but not published then add it to the _draft folder. All media ssuch as pictures, animated gifs and videos hould be added to the assets folder.

## Setup locally

Run `docker-compose up -d` from the root folder. The site should be available locally on [http://localhost:4000](http://localhost:4000). Live reloading is enabled and changes done in code base should reflect in the site (few seconds to reload).

#### Site details
Add your site and author details in `_config.yml`