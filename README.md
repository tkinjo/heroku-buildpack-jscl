heroku-buildpack-jscl
===



Example
---

Using a custom Buildpack.

```
$ heroku buildpacks:set https://github.com/ddollar/heroku-buildpack-multi
```




`.buildpacks`

```
https://github.com/heroku/heroku-buildpack-nodejs
https://github.com/tkinjo/heroku-buildpack-jscl
```





Generated `~/public/js/jscl.js`.






Not Implemented
---

 - Auto update.
 - Change output directory by ENV_VAR.
 - Minify.





License
---

The MIT License (MIT)
