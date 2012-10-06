<!--
{
    "title":"Get Started",
    "date":"2012-10-06 16:35",
    "comments":true,
    "categories":[""]
}
-->

## Installation

    npm install wanna -g

## Create a new blog

1.  Create your blog directory:

        mkdir blog
        cd blog

2.  Initialize with wanna

        wanna init

## Configuration

Edit the `config.json` file.

This is an example of my blog configuration blow:

    {
        "title":"ShaoShuai.me",
        "subtitle":"若为自由故",
        "author":"Shawn<shaoshuai0102@gmail.com>",
        "keywords":"shaoshuai.me, blog，互联网, 前端, 技术, 邵帅的博客",
        "description": "邵帅的博客，对互联网、思维感兴趣，热爱生活，一直在路上",
        "theme":"default",

        "disqus_shortname": "shaoshuaime",

        "rsync_username": "root",
        "rsync_host": "shaoshuai.me",
        "rsync_path": "/var/www/blog.shaoshuai.me"
    }


## Write a post

Now we can begin to write. Type in the terminal:

    wanna write

## Preview

    wanna view

## Publish

    wanna publish

## What's next?

