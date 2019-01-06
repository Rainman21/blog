---
title: Getting started with Electron
date: 2018-12-29 14:36:40
tags:
---

## Getting Started

Electron give you a nice way to combine a node js Client-server into a portable application.

Best resource is https://electronjs.org/docs/tutorial/first-app

---

## Integrating with D3js version 4


There are a few examples on the net with D3v3, including one that claims there are issues with including in electron application.  I found the following link helpful (but after downloading realized it is still version 3 of D3)

+ <https://github.com/zz85/space-radar.git>

---

## Trying to avoid breaking upgrades on old project...



Started by getting rid of the ^updating options in the package.json, but it resulted in some security warnings:

> npm WARN notice [SECURITY] electron has the following vulnerabilities: 2 critical, 1 high. Go here for more details: https://nodesecurity.io/advisories?search=electron&version=1.7.8 - Run `npm i npm@latest -g` to upgrade your npm version, and then `npm audit` to get more info.


+ I ran ```npm i npm@latest -g```
+ Then ```npm audit```

```bash Results of npn audit
# Run  npm install --save-dev electron@4.0.0  to resolve 3 vulnerabilities
SEMVER WARNING: Recommended action is a potentially breaking change
  Critical        Remote Code Execution
  Package         electron
  Dependency of   electron [dev]
  Path            electron
  More info       https://nodesecurity.io/advisories/732

  High            Code Execution by Re-enabling Node.js integration
  Package         electron
  Dependency of   electron [dev]
  Path            electron
  More info       https://nodesecurity.io/advisories/574

  Critical        Remote Code Execution
  Package         electron
  Dependency of   electron [dev]
  Path            electron
  More info       https://nodesecurity.io/advisories/563

found 3 vulnerabilities (1 high, 2 critical) in 631 scanned packages
  3 vulnerabilities require semver-major dependency updates.
```

Then followed the recommendation to update Electron to version 4

```
npm install --save-dev electron@4.0.0
```

Then, after rerunning ```npm audit``` 

```
                      === npm audit security report ===

found 0 vulnerabilities
 in 611 scanned packages

```
---
## Building the Electron App

Noticed that examining the package.json file, the developer already wrote scripts for building... you can hover over the script in package.json and run it...

To build electron for windows, it offered the following script