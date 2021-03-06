[![Build Status](https://travis-ci.org/GTNewHorizons/TinkersConstruct.svg?branch=1.7.10)](https://travis-ci.org/GTNewHorizons/TinkersConstruct)

#TINKERS' CONSTRUCT IS UNDERGOING A REWRITE
The current 1.7.10 version of Tinkers' Construct is the final one for this iteration. Only major bugs will be fixed.
The rework is aimed at 1.8 and has no time-plan. It'll be ready when it's done.

#[Tinkers' Construct](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2218638-tinkers-construct)

Modify all the things, then do it again!   
Melt down any metals you find. 	 
Power the world with spinning wind!

##Development
Install Forge as usual, and setup your IDE as with any other Forge project. Forge Multipart, and CClib must be installed from the  Forge File Server: The DEVELOPMENT version of NEI must be installed to the same directory from [Chicken Bones Site](http://www.chickenbones.craftsaddle.org/Files/New_Versions/links.php). Copy `TCore_dummy.jar` to `forge/mcp/jars/mods/` to enable the Preloader (optional -- only needed when working on the preloader itself)

## IMC
All IMC support and examples can be found here: https://gist.github.com/bonii-xx/e46f9d9e81e29d796b1b

##Compile from Source
Note: Git MUST be installed and in the system path to use our scripts.
* Setup: Run [gradle]in the repository root: `gradlew[.bat] [setupDevWorkspace|setupDecompWorkspace] [eclipse|idea]`
* Build: Run [gradle]in the repository root: `gradlew[.bat] build'
* If obscure Gradle issues are found try running 'gradlew clean' and 'gradlew cleanCache'

##Issue reporting
Please include the following:

* Minecraft version
* Tinkers' Construct version
* Forge version/build
* Versions of any mods potentially related to the issue 
* Any relevant screenshots are greatly appreciated.
* For crashes:
	* Steps to reproduce
	* ForgeModLoader-client-0.log (the FML log) from the root folder of the client

##Licenses
Most code is public domain under [Creative Commons 0](http://creativecommons.org/publicdomain/zero/1.0/). The rework will be licensed under the [MIT License](https://tldrlegal.com/license/mit-license)

Textures and binaries are licensed under [Creative Commons 3](http://creativecommons.org/licenses/by/3.0/).

Any modpack which uses Tinkers' Construct takes **full** responsibility for user support queries. For anyone else, we only support official builds from the main CI server, not custom built jars. We also do not take bug reports for outdated builds of Minecraft.

If you have queries about any license or the above support restrictions, please drop by our IRC channel, #TinkersConstruct on irc.esper.net

Any alternate licenses are noted where appropriate.

##Jar Signing
Some jars from our build servers may be signed. Under no circumstances does anyone have permission to verify the signatures on those jars from other mods. The signing is for informational purposes only.
