### CDN Guide

# Theme Css use

/_ ===================================
Root
====================================== _/
**@import url("https://cdn.jsdelivr.net/gh/susanadhikary/GtaServerAssets@main/assets/css/theme.css");**

in main css file and to call variable

**var(--[variable])**
eg. background-color: var(--primary);

## To Call CDN Assets

# you can call all Assets eg.js,css,images...

**https://cdn.jsdelivr.net/gh/susanadhikary/GtaServerAssets@main/[folderstructure]/[filename]**
eg. background-image: "url('https://cdn.jsdelivr.net/gh/susanadhikary/GtaServerAssets@main/assets/images/logo/logo.svg')"
