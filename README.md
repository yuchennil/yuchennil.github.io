# https://yuchenl.in/

This website is built with Hexo and hosted on Github Pages at http://yuchennil.github.io/. SSL encryption is provided by Cloudflare and DNS registration by Google Domains.

As of 2020/01, Github Pages requires user pages to be hosted in `master`. Hence we need to keep all source in another branch `develop`, then deploy _just the webpage_ to `master`.

Compile and start a local server from `develop`

    $ hexo server

Deploy from `develop` to `master`

    $ hexo deploy