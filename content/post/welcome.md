+++
date = "2017-05-24T17:11:09+01:00"
title = "A Website for a meetup"

+++

As many of you might know, [Meetup.com](https://www.meetup.com/Kubernetes-London/) is great to organise your meetup, but not so much to keep details about talks, speakers and sponsors. That's one of the main reason [Milos](https://twitter.com/milosgajdos), [Peter](https://twitter.com/peteridah) and [myself](https://twitter.com/ipedrazas) have decided that perhaps having a website it will more helpful.

We will keep using [Meetup.com](https://meetup.com) for the meetup organisation/notifications, so, what can you expect to find in this website? we will be adding events, articles, sponsor related content, and resources we think could be valuable for the Kubernetes (London) community. Suggestions are always welcome!

**Techie details:** this website is created using [Hugo](https://gohugo.io) and yes, it runs in kubernetes (a cluster running version 1.6.4 in GKE at the time of writing this post). The build is done in a [drone.io](https://drone.io) instance that it also runs in kubernetes and the deployment is done using [helm](https://github.com/kubernetes/helm). The website has a [public repo](https://github.com/KubeLondon/london.k8s.uk) where you can file issues, send PRs or find how we [build and deploy it](https://github.com/KubeLondon/london.k8s.uk/blob/master/.drone.yml#L25).

