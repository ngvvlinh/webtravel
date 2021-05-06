+++
title = "Explore Con Son Eco-Tourism based community – “Mekong Delta culture conservation”"
description = ""
tags = [
    "go",
    "golang",
    "hugo",
    "development",
]
date = "2020-04-02"
categories = [
    "Development",
    "golang",
]
image = "chonoi1.jpg"
+++

## Introduce

Mekong delta is one of the best places to experience travel for those who love nature and peace. Mekong delta tourism is very diverse with many different destinations that you can choose from. Con Son tourism is one of the most impressive tours of Can Tho which not only brings a lot of culinary experiences but also cultural history of local people. 

Save it somewhere specific as we will be using it in the next step.

More complete instructions are available at [Install Hugo](https://gohugo.io/getting-started/installing/)

## Step 2. Build the Docs

Hugo has its own example site which happens to also be the documentation site
you are reading right now.

Follow the following steps:

 1. Clone the [Hugo repository](http://github.com/spf13/hugo)
 2. Go into the repo
 3. Run hugo in server mode and build the docs
 4. Open your browser to http://localhost:1313

Corresponding pseudo commands:

```shell
    git clone https://github.com/spf13/hugo
    cd hugo
    /path/to/where/you/installed/hugo server --source=./docs
    > 29 pages created
    > 0 tags index created
    > in 27 ms
    > Web Server is available at http://localhost:1313
    > Press ctrl+c to stop
```

Once you've gotten here, follow along the rest of this page on your local build.

## Step 3. Change the docs site

Stop the Hugo process by hitting Ctrl+C.

Now we are going to run hugo again, but this time with hugo in watch mode.

```shell
    /path/to/hugo/from/step/1/hugo server --source=./docs --watch
    > 29 pages created
    > 0 tags index created
    > in 27 ms
    > Web Server is available at http://localhost:1313
    > Watching for changes in /Users/spf13/Code/hugo/docs/content
    > Press ctrl+c to stop
```

Open your [favorite editor](http://vim.spf13.com) and change one of the source
content pages. How about changing this very file to *fix the typo*. How about changing this very file to *fix the typo*.

Content files are found in `docs/content/`. Unless otherwise specified, files
are located at the same relative location as the url, in our case
`docs/content/overview/quickstart.md`.

Change and save this file.. Notice what happened in your terminal.

```shell
    > Change detected, rebuilding site

    > 29 pages created
    > 0 tags index created
    > in 26 ms
```

Refresh the browser and observe that the typo is now fixed.

Notice how quick that was. Try to refresh the site before it's finished building. I double dare you.
Having nearly instant feedback enables you to have your creativity flow without waiting for long builds.

## Step 4. Have fun

The best way to learn something is to play with it.
