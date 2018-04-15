+++
title = "Infrastructure"
date = "2016-11-27"
+++

Founable is a open source static sites generated via hugo.io. It is hosted in GitHub with GitHub Page and domain by Google

This site was initially created with Jekyll but i decided to switch it to [HUGO](https://gohugo.io) because i find that it is easier to use.

I am using mac osx and i use [Homebrew](https://brew.sh/) which make it easy to install those software but still it has dependency. Jekyll depend on Ruby. I also have to use bundle when using Jekyll.

HUGO is created with [Go Programming Language](https://golang.org/) with no other dependency. Theme with HUGO super easy, i just have to clone the repo and update the config.toml. When i have bad markdown , it will not compile and show me the error which i love it a lot

A few command that make me like HUGO more than Jekyll

Run local server with Jekyll

```bundle exec jekyll serve
```

Run local server with HUGO

```hugo server
```

Build with Jekyll

```jekyll build --destination <destination>
```

Build with HUGO

```hugo --destination <destination>
```