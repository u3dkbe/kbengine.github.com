---
layout: docs
title: Script Programming · Docs · KBEngine
tab: docs
docsitem: sdk-client-programming
---

Client-SDK Programming
====================


###Client Types

	Defined in kbengine/kbe/src/lib/cstdkbe/cstdkbe.hpp:
	enum COMPONENT_CLIENT_TYPE
	{
		// Mobile(Phone, Pad)
		CLIENT_TYPE_MOBILE				= 1,

		// Windows/Linux/Mac Application program
		// Contains the Python-scripts, entitydefs parsing and check entitydefs-MD5, Native
		CLIENT_TYPE_PC					= 2,

		// Web，HTML5，Flash
		// not contain Python-scripts and entitydefs analysis, can be imported protocol from network
		CLIENT_TYPE_BROWSER				= 3,

		// bots(Contains the Python-scripts, entitydefs parsing and check entitydefs-MD5, Native)
		CLIENT_TYPE_BOTS				= 4,

		// Mini-Client
		// Allowing does not contain Python-scripts and entitydefs analysis, can be imported protocol from network
		CLIENT_TYPE_MINI				= 5,
		...
	};


###Server errors:
Please to see: [server_errors.xml]



[server_errors.xml]: {{ site.baseurl }}/docs/configuration/server_errors.html