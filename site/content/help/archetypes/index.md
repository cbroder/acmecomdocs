---
date: 2016-04-09T16:50:16+02:00
prev: /help/shortcodes
next: /contributing
title: Archetypes

toc: true
weight: 25
icon: "<b>2. </b>"
---

Using the command: `hugo new [relative new content path]`, you can start a content file with the date and title automatically set. While this is a welcome feature, active writers need more : [archetypes](https://gohugo.io/content/archetypes/).


## Chapter

To create a Chapter page, run either one of the following commands

```
# Either
hugo new --kind chapter <name>/index.md
# Or
hugo new --kind chapter <name>.md
```

It will create a page with predefined Front-Matter:

    ---
    chapter: true
    date: 2016-04-10T23:17:49+02:00
    icon: <b>X. </b>
    next: /next/path
    prev: /prev/path
    title: index
    weight: 0
    ---

    ### Chapter X

    # Some Chapter title

    Lorem ipsum


## Default

To create a default page, run either one of the following commands

```
# Either
hugo new <chapter>/<name>/index.md
# Or
hugo new <chapter>/<name>.md
```

It will create a page with predefined Front-Matter:

    ---
    date: 2016-04-09T17:51:50+02:00
    next: /next/path
    prev: /prev/path
    title: index
    toc: true
    weight: 5
    ---

    Lorem Ipsum

*Don't forget that Hugo-theme-learn supports only one level under a chapter*
