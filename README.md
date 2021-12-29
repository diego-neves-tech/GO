# diego-crawler

## Usage
```
$ make setup
$ make build && ./diego-crawler sedna.com | tee sitemap.txt
$ less sitemap.txt
```

## Problem Statement
Write a simple web crawler in a programming language of your choice. The crawler should be limited to one domain - so when crawling SEDNA.com it would crawl all pages within the domain, but not follow external links, for example to the LinkedIn and Twitter accounts. Given a URL, it should output a site map, showing which static assets each page depends on, and the links between pages.​