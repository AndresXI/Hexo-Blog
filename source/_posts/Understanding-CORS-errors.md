---
title: Understanding CORS errors
date: 2019-01-24 19:51:07
tags:
- CORS
- Errors
- HTTPS
- HTTP Headers
- APIs
---

Cross-Origin Resource Sharing (CORS) is a security mechanism that is used by the browser to protect itself from API requests created from a different source (a source hosted on another server). For example say you're working on a web application that uses Spotify's API to request some information about an artist, here you have to different origins (sources) trying to exchange some information. In order for this process to be successful the browser needs to know if it is safe to do so, here is where CORS comes in. If you dont' set any additional headers on your request you could receive the following error:  

<img src="https://raw.githubusercontent.com/AndresXI/Hexo-Blog/master/cors.png" height="800">
