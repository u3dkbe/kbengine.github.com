---
layout: docs
title: Stress Test · Docs · KBEngine
tab: docs
docsitem: documentation-stresstest
---

Stress Test
====================

Use the virtual client, and uses the same game logic, so that a large number of players 
login the robot simulation game server, we can observe that the server is running condition, 
with debug to find bottlenecks.


Start bots
--------------------------------------

	[kbe@gameserver ~]$ ./bots &

Or use script:
--------------------------------------

	kbe/bin/Hybrid/!warringstart_bots.bat
	kbe/bin/Hybrid64/bots_start.sh



Configuration Bots
--------------------------------------

see also [kbengine_defs.xml]->`bots`



------------------------------------------------------------------------------------------------------------


Robot programming
====================

Reference: demo/res/scripts/[bots] script-sources.



[kbengine_defs.xml]: {{ site.baseurl }}/docs/configuration/kbengine_defs.html
[bots]: {{ site.baseurl }}/docs/concepts/directorys.html
