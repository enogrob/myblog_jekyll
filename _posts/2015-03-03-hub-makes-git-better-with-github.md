---
layout: post
title:  "Hub makes git better with github"
date:   2015-03-03 20:47:00
categories: apps
---
![Hub Logo](/assets/hub.png)

`hub` is a command-line wrapper for git that makes you better at GitHub. Whether you are beginner or an experienced contributor to open-source, hub makes it easier to create or fetch repositories, navigate project pages, fork repos and even submit pull requests, all from the command-line.

An example using `hub` in order to create a repo:
```bash
git init
git add .
git commit -m "First commit"
git create "DS_Exploratory_Data_Analysis"
```

As `git` has an alias of `hub` in the subcommand `create` the command `hub` is executed giving an impression that git was extend with new subcommands.

Here it is another example, where it is even possible opening the GitHub homepage from the command line.
```
git browse .
```

Homepage: [Hub](https://hub.github.com)

