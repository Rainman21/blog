---
title: New System Setup - Node
date: 2018-12-31 15:54:39
tags: 
- Setup
- Node
categories:
- Setup
- Node
---
## Node Setup

First, you bootstrap everything by first installing NodeJS, which should be easily found via search.  The last URL used was:

> <https://nodejs.org/en/download/>

## Determining your favorite node modules from an existing computer
Usually, I forget what Node modules I've installed so I like to get a list so I can then create a batch file for loading all the common ones I use. To List, try

> ```npm list -g --depth 0```

```
>npm list -g --depth 0
C:\Users\***\AppData\Roaming\npm
+-- electron-packager@13.0.0
+-- eslint@5.8.0
+-- express@4.16.3
+-- fs@0.0.1-security
+-- hexo-cli@1.1.0
+-- http-server@0.11.1
+-- markdown@0.5.0
+-- markdown-to-html@0.0.13
+-- call npm@6.5.0
`-- typescript@3.0.1
```

to see which packages are out of date try

> ```npm outdated -g --depth=0```

```
Package            Current  Wanted  Latest  Location
electron-packager   13.0.0  13.0.1  13.0.1
eslint               5.8.0  5.11.1  5.11.1
express             4.16.3  4.16.4  4.16.4
typescript           3.0.1   3.2.2   3.2.2
```

you can update all global packages via 

> ```npm update -g```
 
## Favorite Node Modules

If you want to install by batch file, you must use 'call' because npm is also a batch file

```

Echo --- Basic High level utils ---

call npm install -g yarn
call npm install -g npx
call npm install -g np
call npm install -g npm-name-cli
call npm install -g fs
call npm install -g express
call npm install -g http-server

Echo --- Hexo and Markdown to HTML ---

call npm install -g hexo-cli
call npm install -g markdown-to-html
call npm install -g markdown

Echo --- Electron ---

call npm install -g electron-packager

Echo --- Debugging ---

call npm install -g ndb
call npm install -g node-inspector

Echo --- Low Level utils ---
call npm install -g tldr
call npm install -g now
call npm install -g spoof
call npm install -g fkill-cli
call npm install -g castnow
call npm install -g github-is-starred-cli
call npm install -g vtop

Echo --- React ---

call npm install -g create-react-app
call npm install -g create-react-library
call npm install -g react-native-cli
call npm install -g gulp
call npm install -g less

Echo --- Lint ---

call npm install -g eslint
call npm install -g babel-eslint
call npm install -g eslint-config-standard
call npm install -g eslint-config-standard-react
call npm install -g eslint-config-standard-jsx
call npm install -g eslint-plugin-react
call npm install -g eslint-config-prettier
call npm install -g eslint-plugin-prettier
call npm install -g prettier
call npm install -g standard

Echo --- Typescript ---
call npm install -g typescript

```