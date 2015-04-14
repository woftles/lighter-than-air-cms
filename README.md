_WARNING: I haven't finished ripping all of the code off of my website yet._

#Lighter Than Air CMS
The blog content management system for elitist asshole developers.
It's dynamic because you don't get enough traffic to warrant static webpages.
It's flat-file because I don't know how to work with databases and you probably don't enjoy it much.
It has a php interface because you don't want to learn how to use it like with other elitist asshole content management systems.

##Key Features:
 * Minimum overhead
 * Blog post metadata
 * Blog posting interface
 * No databases (file operated)

##Things I need to do:
 * Secure posting interface so it can be used online
 * Add category groups
 * Refactor everything
 * Refactor everything again
 * Blog post editing/removal interface
 * Re-implement Atom feed generation 


##CMS Architecture
	Root
		content
			posts
				0001-default-title.md
				0002-second-post.md
			images
				test.png
			blog-meta.json
			atom.xml
		js
			jquery-1.11.2.min.js
			pagedown.js
		lta-cms
			lta-front.js
			lta-back.php
			parsedown.php
			interface.php
		css
			example.css
		index.php
		.htaccess

##Blog post metadata format
	{
		"TITLE": "Default",
		"DATE": 0,
		"UPDATED": 0,
		"ID": "tag:whitecollargames.com,1970-01-01:0:1",
		"CATEGORIES":[]
	}
