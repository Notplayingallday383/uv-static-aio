<p align="center"><img src="https://raw.githubusercontent.com/titaniumnetwork-dev/Ultraviolet-Static/main/public/uv.png" height="200"></p>

<h1 align="center">Ultraviolet-Static-AIO</h1>

A completely static version of Ultraviolet-static ready for deployment with minimal changes

## Setup

Alright to set this up you can basically do it on any static host site. First, Fork this repo and in your fork go over to `public/register-sw.js` and go down untill you find 

```js
// This is the line you change to change the wisp server (essential for static hosting ofc)
let wispUrl = "ws://nebulaproxy.io/wisp/"
```

Once you found that line change the wisp url to something else. 

> [!IMPORTANT]  
> Do **NOT** create tickets, issues, ping or ask "where can I make a wisp-server". If your trying to do that litterally just deploy [Ultraviolet-app](https://github.com/titaniumnetwork-dev/ultraviolet-app) Its not that hard to do and is already basically setup for you to use.

And finally go to deploy it and set the **output** directory to: `public\` and leave the rest blank.

### Credits

- &copy; Copyright 2024 Titanium Network
- XSTARS was here
