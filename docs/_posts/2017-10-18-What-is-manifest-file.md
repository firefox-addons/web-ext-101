---
layout: post
title: What is manifest.json file
date: 2017-10-18 00:05:00
tags: whatis
category: blog
---

**manifest.json** is very important file and each and every extension we develop should have it. It is a JSON(JavaScript Object Notation) file.

For each and every Extension below list of the things are mandatory.

- manifest_version
- version
- name
- description


name
====

Name of the Extension we are developing. This is used to identify easily in browser where there is installed Add-ons listing and also in addons.mozilla.org (AMO) where we will upload our Add-ons so Firefox users can download.


	"name" : "my First WebExtension"


description
===========

It is very short description of the Extension we are developing. Give a meaning full name for this.


	"description" : "this add-on will be changing the new tab page"


version
=======

Version of the Add-on we are going to develop. It should be incremental each time we upload to AMO.


	"version" : "1.0"


Lets make sure we are giving mostly in major.minor format (like above), else if we want to do more detailed on major.minor.release.build 

manifest_version
================

This is version of manifest.json. This is defined by Mozilla (Chrome also). And as on Oct 2017 it should be 2

	"manifest_version": 2


Look at Below one


	{
	
		"name" : "my First WebExtension",
		"description" : "this add-on will be changing the new tab page",
		"version" : "1.0",
		"manifest_version": 2
	}


Beyond this
===========

These above defined are very minimum and mandatory for all the Extension. Beyond this we are having different keys which we will be exploring as the example comes. 

