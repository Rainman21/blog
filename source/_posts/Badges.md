---
title: Badges
date: 2019-01-03 23:34:19
tags:
---

```html
<svg xmlns="http://www.w3.org/2000/svg" width="99" height="20">
    <linearGradient id="a" x2="0" y2="100%">
        <stop offset="0" stop-color="#bbb" stop-opacity=".1"/>
        <stop offset="1" stop-opacity=".1"/>
    </linearGradient>
    <rect width="99" height="20" fill="#555" rx="3"/>
    <rect width="36" height="20" x="63" fill="#97CA00" rx="3"/>
    <path fill="#97CA00" d="M63 0h4v20h-4z"/>
    <rect width="99" height="20" fill="url(#a)" rx="3"/>
    <g fill="#fff" font-family="DejaVu Sans,Verdana,Geneva,sans-serif" font-size="11" text-anchor="middle">
        <text x="32.5" y="15" fill="#010101" fill-opacity=".3">
            coverage
        </text>
        <text x="32.5" y="14">
            coverage
        </text>
        <text x="80" y="15" fill="#010101" fill-opacity=".3">
            97%
        </text>
        <text x="80" y="14">
            97%
        </text>
    </g>
</svg>
```