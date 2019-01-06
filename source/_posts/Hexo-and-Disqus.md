---
title: Hexo and Disqus
date: 2019-01-05 15:13:23
tags:
- Sites
- Hexo
- Comments
categories:
- Sites
- Hexo
- Comments

---
## Enabling Discussions on Hexo via Disqus

Depending upon the theme you are using, you may be able to drive it purely by theme yaml, as in the case of Next theme. Not sure if this is because Next theme is done using swig and not ejs.

```yaml
disqus:
  enable: true
  shortname: sprenk
  count: true
  lazyload: false
```

To setup your site, go to disqus.com and register for free account, and configure your site.  This is a ==two step== process: 
+ setup account
+ setup site

When setting up the site, you get to pick a shortname and associate it with your site / site URL
