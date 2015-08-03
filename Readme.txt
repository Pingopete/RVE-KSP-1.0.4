# RVE-KSP-1.0.4 - For Linux(x64) users only
RVE for KSP 1.0.4 | RSS 10.2+ | EVE Overhaul (latest)

DO NOT BUG REPORT UNLESS THE ISSUE HASN'T BEEN LISTED BELOW -- OR YOU GAME LITERALLY DOESN'T WORK - THIS IS A WORK IN PROGRESS!
If reporting please first state which version of RVE you're trying to run (i.e. Windows32 or Linux64)
Requirements:
	KSP 1.0.4
	RSS 10.2:
	> http://forum.kerbalspaceprogram.com/threads/55145-1-0-4-Real-Solar-System-v10-2-July-30

	Necessary EVE files *NOT* included; you will need:
	EnvironmetalVisualEnhancements folder from the latest EVE overhaul branch (Download the Zip of that branch then drag 	the EnvironmentalVisualEnhancements folder, from that zip, into your gamedata folder). Download the EVE-Overhaul branch 		from:
	> https://github.com/rbray89/EnvironmentalVisualEnhancements/tree/Overhaul

	Scatterer (Latest)
	> http://forum.kerbalspaceprogram.com/threads/115408-WIP-Scatterer-atmospheric-scattering-(v0-0171-18-07-2015)-Kept-you-waiting-huh

	No other cloud configs present in gamedata e.g. like in BoulderCo folder.
  
Recommended:
  PlanetShine
  WindowShine
  Distant object enhancements
      (for appropriate planet and skybox brightness)
  A custom Skybox
      (Blubber monkey's and Proots are the best IMO)
  CameraTools
  
Installation/use:
 0- This probably won't work if you're not on Linux x64 and with at least 4-8GB RAM 
 1- Download the Linux-Branch Zip
 2- Install all required mods first
 3- Place all RVE folders from Zip into your Gamedata folder (overwriting)
 4- Place shared assets file into your KSP_data folder for RVE sun and lens flare
  - Ignore .git and README.md looking files
  - You may need to go to launchpad/Runway before switching to craft in space
  - Read known bug list
 5- Enjoy.. maybe.. ;)

KnownIssues/WIP Areas
  EVE-GUI APPLY WILL CAUSE SERIOUS BUGS WHEN IN ORBIT
  No other planets worked on other than Earth (and that's only half done)
  ScaledSpace/Orbital ground textures are a WIP
  EVE Terrain GUI section does not apply or write to config
  Flashing clouds from orbit
  Extremely High memory usage.. (can be up to 9GB with mods) .. so will NOT work on Win32,Mac or with Win-openGL.
  Shadows for cloud texture are very memory intensive and can cause crashing even on linux64, if you're crashing hard try disabling them in EVE GUI (Alt+E)
  Extremely bright atmosphere and/or ground once in space -Scatterer problem
  Discolouration of ground haze when in atmosphere -Scatterer OpenGL problem
  Cloud shadows remain at terminators and appear where clouds hit terrain
