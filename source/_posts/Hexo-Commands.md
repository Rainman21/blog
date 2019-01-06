---
title: Hexo Commands
date: 2018-12-29 00:01:04
tags:
---
# Hexo Commands

If find it easiest to work in VS Code and use multiple terminals...

### AutoGeneration
To setup for autogeneration use

> ```hexo generate --watch```


you get the following showing up in the console:
```yaml
INFO  Generated: archives/2018/12/index.html
INFO  Generated: 2018/12/27/Interesting-Hexo-Plugins/index.html
INFO  Generated: 2018/12/29/Hexo-Commands/index.html
```
## Creating new Pages and posts

To create a new post

> ```hexo new [page|post] "title with spaces"```

## Running the server

To run the server locally with logging use

> ```hexo server -l```

you get output like

```YAML
D:\Software\hexo\blog>hexo server -l
INFO  Start processing
INFO  Hexo is running at http://localhost:4000 . Press Ctrl+C to stop
```