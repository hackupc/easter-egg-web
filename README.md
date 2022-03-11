# HackUPC easter egg script for webs

[![Netlify Status](https://api.netlify.com/api/v1/badges/fc5058a6-61a5-40c9-9598-d1b8636878ee/deploy-status)](https://app.netlify.com/sites/hackupc-easter-egg/deploys)

<p align="center">
  <img width="615" alt="" src="https://user-images.githubusercontent.com/12821361/157764642-baeb4311-fb6f-46f9-9e2d-fd8e1c1fbfb4.png">
  <img width="828" alt="" src="https://user-images.githubusercontent.com/12821361/157776242-c6203046-e007-4b04-94bf-a0c885a6b77e.png">

</p>

Confuse hackers by adding this script in a website. It does the following:
1. Prints a cool banner into the console.
1. Adds an element with a weird name at the end of the body that contains a custom text.
1. Deletes the `<script>` from the page, so hackers can't find it.

## Usage

Add this code at the bottom of the `body`:

```html
<script async src="https://easter-egg.hackupc.com/index.js"></script>
```

## Develop
1. Install Node.js (with `vnm`).
1. Clone the repo and open it.
1. Run `npm install` to install the dependencies.
1. Code.
1. Run `npm run build` to build.
1. To deploy, just push to `main` and [Netlify](https://api.netlify.com/api/v1/badges/fc5058a6-61a5-40c9-9598-d1b8636878ee/deploy-status) will handle the rest automatically.
