---
layout: post
title: What are WebExtension
date: 2017-10-18 00:00:00
tags: whatis
category: blog
---

In 2015 Firefox team has made an exciting very big announcement to Firefox add-ons, they have brought a new extension API's called [WebExtension](https://wiki.mozilla.org/WebExtensions).  This update has lot of exciting announcements for developers.

1. Review process will become faster
2. Development is easier, and the Addons will be compatible with Chrome and Opera.

You can find the whole information regarding this update in Add-ons [Blog](https://blog.mozilla.org/addons/2015/08/21/the-future-of-developing-firefox-add-ons/).

The next step is to download the Firefox Browser and install them. You can either go for [developer Edition](https://www.mozilla.org/en-US/firefox/developer/) or [Nightly](https://nightly.mozilla.org/)

So as of now Firefox Will allow only the add-ons which are signed when you start the browser. So for development purpose we have to change the settings.

1. Open the browser
2. in the URL bar type about:config

![config in URL bar]({{ site.url }}/assets/img/config.png)

![Warning]({{ site.url }}/assets/img/warning.png)

3. In the search bar of that page type xpinstall.signatures.required , you will see the image as like below. By default it will be true

![Signature]({{ site.url }}/assets/img/signature.png)

4. You can double click on it or else right click and select toggle. So it will be set to false

