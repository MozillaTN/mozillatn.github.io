---
title:  "Writing My First Extension (Firefox Add-ons)"
date:   2016-03-10 02:20:00
description: Developing First WebExtension
categories: clubs
tags: [addons,firefox]
author: iamvp
---

In last post I was writing about [Getting Started with WebExtension]({{ site.url/2016/02/Lets-Get-Started-With-WebExtensions/}}). Its very exicting to learn something new in Web each and everyday. And as a developer the feel when we know our software (General term you can replace with WebExtension)  is going to reach many users its awesome feeling.

Often many times I have the habit of visiting some website daily and very frequently. So I decided to have top three websites I visit and open them in a single click. I developed an Add-on which will be opening the websites choosen.

So the main API which do this action is n

> _chrome.tabs.create({"url": chrome.extension.getURL(domain)});_

The above API is for Firefox Add-on and for Chrome we have slightly little bit different API
	
> _chrome.tabs.create({"url": domain});_

And in the manifest file there was a minor change, the below line should be there in the Firefox Extension while it need not be there in the Chrome manifest file. 

`"applications": {
    "gecko": {
      "id": "shihan.viswa@gmail.com"
    }
  },`

You can download the [Source code](https://github.com/iamVP7/MyExtensions/tree/master/tabopen) of this Add-on and use for your favorite top website which you want quick access.

In the upcoming post will share more details about the code flow of this Extension and also we can try different API.
