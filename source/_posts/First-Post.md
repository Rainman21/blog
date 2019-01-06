---
title: First Post Testing Markdown
date: 2018-12-27 14:49:46
tags: hexo
---

## Why Hexo

Found this article that tended to reinforce the initial idea to move to hexo:

<https://oded.blog/2017/07/11/From-Ghost-to-Hexo/>

https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/

https://www.poweredbyjeff.com/2018/05/14/Deploying-Hexo-website-to-Github-Pages/

## Good Markdown Cheatsheet
<https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>

Supported Code Syntax (default highligher is highlightjs)
> <https://highlightjs.readthedocs.io/en/latest/css-classes-reference.html>

You can switch to the prism highlighter and default to Prism


asciidoc, cpp, csharp -- see https://prismjs.com/#languages-list
```cpp MyClass with spaces http://underscorejs.org/#compact Underscore.js
class MyClass
{
    //Test Comment
    public int X {get;set;};
    bool GetMyVal(int x);
}
```

# H1
## H2
### H3

{% codeblock lang:objc %}
[rectangle setX: 10 y: 10 width: 20 height: 20];
{% endcodeblock %}

```yaml title http://google.com google
INFO  Generated: css/main.css
INFO  Generated: index.html
INFO  Generated: 2018/12/27/First-Post/index.html
INFO  Generated: css/main.css
INFO  Generated: index.html
INFO  Generated: 2018/12/27/First-Post/index.html
INFO  Generated: css/main.css
```

testing tables
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |