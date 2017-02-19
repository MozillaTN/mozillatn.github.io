---
title:  "Add yourself as Author"
date:   2016-04-05 02:20:00
description: Add as author for Community Blog
categories: blog
tags: []
author: mozillatn
---

On April 1st MozillaTN community released new version of the [Website](http://mozillatn.github.io/). The main aim of this website is to bring all the community related or contribution related materials at one place. As a first step we have successfully integrated our community blog here. So this website in future will have details like active club in Tamilnadu, how to get started with various contribution areas, details about task force members of Tamilnadu community and much more.

So we are now bring authors who will contribute to this website in future. These authors can be Mozilla Reps, Firefox Student Ambassadors, FSA Club leads, or Open source contributor. Yes we are not restricting much.

	1. So The First step is visit our [MozillTN repo in Github](https://github.com/MozillaTN/mozillatn.github.io) to your github profile
	2. Goto people.yml file which will be under _data_ , in my [repo](https://github.com/iamVP7/mozillatn.github.io/blob/master/_data/people.yml).
	3. Click on Pencil like icon, which is Edit this file
	4. Goto the end of the file to add your details. Follow the steps given below
		1. First give the author-nick
		2. Then give the name,twitter,description,gravatar.
		3. In the above listed, author-nick is the author reference you will use in the blog post, so it is mandatory.
		4. Name, twitter handle is mandatory. Description is like about the author. Better to give. following is the example
			 mozillatn
				name: MozillaTN
    				twitter: mozillaTN
    				description: Community
				gravatar: http://www.gravatar.com/avatar/8d6ea5553261cc856bdc2bedf852eb66

so first gave the nick name (mozillatn) and then goto next line, give a intend (ie., press tab once), give name i.e, author name and in next line give twitter handle, then give description.

After finishing this give the heading of the commit information as "Updated author details" and then give the description as "Added Contributor " then your nickname, like "Added Contributor iamvp7" then click on Commit changes.

Then goto pull requests tab, click on New pull request, you will see an image as shown below
![Pull Request Comparision]({{ site.url }}/assets/blog/pullrequest.png)

Then click on Create pull Request. You will be allowed to type the message. 

See that heading is "Updated author details" and the description is like "Added Contributor iamvp7" 

And then we will merge to the main repo in a week, after that you can start contributing blog posts or adding about your clubs.

	

