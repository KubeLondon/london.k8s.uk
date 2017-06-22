# Kubernetes London Meetup

This is the main repo for the Kubernetes London meetup website. If you want to contribute with articles, please open a PR with your article. 


# How to contribute

We use [Hugo](https://gohugo.io/) as our static website generator. There are instructions of how to install Hugo in your system in [this page](https://gohugo.io/overview/installing/).

Once you have Hugo installed, you have to clone our [GitHub repo](https://github.com/KubeLondon/london.k8s.uk). Create a branch to keep your changes tidy:

```
git clone https://github.com/KubeLondon/london.k8s.uk.git
cd london.k8s.uk
git checkout -b my-branch
```

To create a new article you use hugo to create the draft:

```
hugo new post/my-new-article.md
```

This command will create a file in `london.k8s.uk/content/posts/my-new-article.md` with a content very similar to:

```
+++
description = ""
categories = ["event"]
tags = ["kubernetes", "meetup"]
draft = true
date = 2017-06-23T00:29:48+01:00
author = ""
title = "My New Article"
+++

This is my **new article**
```

Once you have the article created and if you want to preview it, you can do it by running the following command:

```
hugo server --buildDrafts
```

If everything looks fine, send us a PR!

