---
layout: docs
title: Server Layout · Docs · KBE
tab: docs
docsitem: concepts-directorys
---

The server directory structure
=============


	|- kbengine							(KBE_ROOT path)
		|- demo							(Root of the game examples of projects)
			|- res						(All resource projects)
				|- spaces				(Usually associated storage resource game scenes, such Navmesh)
				|- server				(Usually placed Server Configuration)
				|- scripts				(All game logic, python file)
					|- base				(Base of Python logic)
					|- cell				(Cell of Python logic)
					|- client			(Client of Python logic)
					|- bots				(Bots of Python logic, Stress Test)
					|- common			(Logic public folders)
					|- data				(Game logic used data resources)
					|- db				(Dbmgr Extended Script)
					|- entity_defs			(Entity definitions and declarations)
						|- interfaces		(Interface declaration entity)
					|- server_common		(Server logic public)
					|- user_type			(Custom user type directory)
		   |- kbe						(Engine Directory)
			|- tools					(Engine Tools)
				|- server				(Server Tools)
					|- guiconsole			(Console visualization tool)
					|- install			(Engine installation tool)
					|- pycluster			(Cross-platform cluster-control Python tool)
				|- xlsx2py				(Game Data Sheet export tool)
			|- src						(KBEngine source code)
				|- build				(Public makefile script)
				|- client				(Client plug-in directory and examples)
					|- kbengine_dll			(Windows application plug-in source code)
				|- common				(Public directory)
				|- lib					(Modules source code)
					|- client_lib			(Client c++ public-framework)
					|- cstdkbe			(The KBEngine standard library)
					|- db_mysql			(Mysql access)
					|- dbmgr_lib			(Data Access Common Interface)
					|- dependencies			(Dependencies)
					|- entitydef			(Entity definition parsing module)
					|- helper			(Helpers)
					|- math				(Math Module)
					|- navigation			(2D/3D navigation module)
					|- network			(Network Module)
					|- pyscript			(Script plug-in)
					|- python			(Python sources)
					|- resmgr			(The resource manager)
					|- server			(Servers public module)
					|- thread			(Thread module)
					|- xmlplus			(Xml parsing)
				|- libs					(Compiled *. Lib, *. A files)
				|- server				(Server-apps sources)
					|- baseapp			(Baseapp sources)
					|- baseappmgr			(Baseappmgr sources)
					|- cellapp			(Cellapp sources)
					|- cellappmgr			(Cellappmgr sources)
					|- dbmgr			(Dbmgr sources)
					|- loginapp			(Loginapp sources)
					|- machine			(Machine sources)
					|- resourcemgr			(Resourcemgr sources)
					|- tools			(The assistant tool)
						|- billing_system	(Support for third-party billing, third-party accounts, etc.)
						|- bots			(Stress test, the virtual client, sources)
						|- guiconsole		(Visualization tool for console, sources)
						|- message_log		(Server log collection tool, sources)
			|- res						(Engine Resource Directory)
				|- key					(RSA key)
				|- scripts				(Python script library)
				|- server				(Server engine configuration)
					|- log4cxx_properties		(Log4cxx configuration)
			|- doc						(Guide document source code)
			|- bin						(Compiled executable files storage directory)
				|- client				(Client.exe executable files storage directory)
				|- Hybrid				(Compiled 32bit-executable files server storage directory)
					|- logs				(Server running log)
				|- Hybrid64				(Compiled 64bit-executable files server storage directory)
					|- logs				(Server running log)
		   |- tutorial						(Guide document)