#Quake Run: Quake 4 Speedrun
#Developed by Jansen Pimentel
# 
#IMPORTANT FILES:
#	-player.def
#	-Quake4Config.cfg
#	-english_guis.lang
#
#EDITED FILES:
#	-Player.cpp
#	-Player.h
#	-Item.cpp
#
#This mod spawns the player with a leg wound. The user must complete the level before bleeding out while fighting monsters on the way. Find health packs to combat your leg wound.
#
#The user can:
#	-sprint by holding right-click as you move.
#	-double jump by pressing the space bar twice.
#	-pick up health packs that give a (10 sec) health regeneration powerup (combats the leg wound)
#	-pick up weapons that give a (10 sec) fire rate boost powerup.
#	-pick up ammo that give a (10 sec) damage boost powerup.
#
#Speedrun rules:
#	-you lose health over time due to your leg wound.
#	-you lose health when jumping due to your leg wound.
#	-your legs are unstable, making it impossible to stand still.
#	-a HUD demonstrating your mind is bouncing to show your health is below max. (test by healing to full by Medic Anderson)
#	-a HUD that will turn red when you're attacked/bleeding.
#	-the HUD will fade away when you are close to death, so the player can see clearer.
