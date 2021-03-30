***
# NOTICE:

## This repository has been archived and is not supported.

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)
***
NOTICE: SUPPORT FOR THIS PROJECT HAS ENDED 

This projected was owned and maintained by Walmart. This project has reached its end of life and Walmart no longer supports this project.

We will no longer be monitoring the issues for this project or reviewing pull requests. You are free to continue using this project under the license terms or forks of this project at your own risk. This project is no longer subject to Walmart's bug bounty program or other security monitoring.


## Actions you can take

We recommend you take the following action:

  * Review any configuration files used for build automation and make appropriate updates to remove or replace this project
  * Notify other members of your team and/or organization of this change
  * Notify your security team to help you evaluate alternative options

## Forking and transition of ownership

For [security reasons](https://www.theregister.co.uk/2018/11/26/npm_repo_bitcoin_stealer/), Walmart does not transfer the ownership of our primary repos on Github or other platforms to other individuals/organizations. Further, we do not transfer ownership of packages for public package management systems.

If you would like to fork this package and continue development, you should choose a new name for the project and create your own packages, build automation, etc.

Please review the licensing terms of this project, which continue to be in effect even after decommission.

# jQuery RWD Image Maps

### Allows image maps to be used in a responsive design by recalculating the area coordinates to match the actual image size on load and window.resize

---

#### Usage:

* If possible, add [correct, unitless](http://dev.w3.org/html5/markup/img.html) `width` and `height` attributes to your image map images. You can override these in CSS to make them responsive.
* Add a link to jQuery in your page, preferably at the bottom just before the closing `</body>`
* After jQuery, either in a `<script>` block or a separate file, call:

```js
$('img[usemap]').rwdImageMaps();
```

You may also want to wrap it inside a `$(document).ready()` function, like so:

```js
$(document).ready(function(e) {
    $('img[usemap]').rwdImageMaps();
});
```

#### Demo:

http://mattstow.com/experiment/responsive-image-maps/rwd-image-maps.html

---

Copyright (c) 2012 [Matt Stow](http://mattstow.com)  
Licensed under the MIT license *(see [LICENSE](https://github.com/stowball/jQuery-rwdImageMaps/blob/master/LICENSE) for details)*  
Minified version created with Online YUI Compressor: http://www.refresh-sf.com/yui/
