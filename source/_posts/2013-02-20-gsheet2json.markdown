---
layout: post
title: "Gsheet2json"
date: 2013-02-20 10:36
comments: true
categories: 
- My Ideas
- Web Application
- Developed
- Open Source

tags:
- html-js
- google-docs

publish-github: https://github.com/rumal/Gsheet2json
publish-web: http://rumal.github.com/Gsheet2json/
img: gsheet2json.png
des: JS object to easily read from publicly hosted Google spreadsheets.
---

Gsheet2json
===========

A Java script object to easily read from publicly hosted Google spreadsheets. You can use it as a database for your web application


###Quick Start

* Download and include [gsheet2json.js](https://raw.github.com/rumal/Gsheet2json/master/js/gsheet2json.js) to your project.
*  
```
var sheet = new spreadSheet(
	            {url to the publicly hosted spreadsheet},
	            {fieldlist as an array},
	            {success function}
	  );
```
* Use `sheet.getAsArray()` or `sheet.getAsObjects()`


###Example

```
<script type="text/javascript" src="js/gsheet2json.js"></script>
<script>
  var fields = ["URL", "Speaker", "Name", "Short Summary", "Event","Duration", "Publish date"];
  var sheet = new spreadSheet(
      "https://docs.google.com/spreadsheet/ccc?key=0AsKzpC8gYBmTcGpHbFlILThBSzhmZkRhNm8yYllsWGc&gid=0",
      fields,
      function(data) {
         console.log(data.getAsObjects());
         console.log(data.getAsArray());
      });
</script>
```

<http://jsfiddle.net/pasindur/EsGmX/>


