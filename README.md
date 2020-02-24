# Rural Revival Website

Created in Dec 2019, this is a port of our old WordPress data over to a [Hugo](https://gohugo.io) static website.

## Content Layout

The majority of the content is in the `content` folder.  Within that are folders and Markdown formated files for each 
pages/news article.  Generally, news stories are stored as a markdown file in a named folder organized by year 
alongside their associated files/images.  See `content/news/2019` as examples to follow.

Some historic documents/attachments are in the `static` directory.  These could be moved, but haven't been.  If minutes 
are added they can be added to that directory as before and referenced using a relative URL (relative to the `static` 
directory).

If developing locally, running `hugo serve` from this base directory will allow for viewing edits very quickly.

To publish to the site, all one needs to do is commit changes to the master branch on github.  Netlify will be 
notified of the changes, and will take care of running the Hugo command and deploy the site live.


## Hosting

[![Netlify Status](https://api.netlify.com/api/v1/badges/b5ce682c-b141-4836-ad58-8937aae94ddb/deploy-status)](https://app.netlify.com/sites/distracted-yalow-765971/deploys)

Netlify is hosting the site, and looking directly [at the repository][1] for changes and is deploying them
automatically.

[1]: https://github.com/paulortman/ruralrevival_website

## Blame

All blame goes to Paul Ortman.
