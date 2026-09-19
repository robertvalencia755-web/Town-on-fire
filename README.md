# Town On Fire

## Overview
This is a game where you (and up to 3 others) are part of a fire company and your task is to go around the city preventing fires, helping out the community, 
and possibly face against unforeseen situations you may or may not have been trained to handle!

## ⚙️ Mechanics Overview
Basic mechanics are as follows:
- Driving around the firetruck to the location of the issues
- loading and unloading the fire hose to attach to the fire hydrant and stop fires
- breaching and going into disaster zones to rescue civilians
- deal with people :p
- handle unique situations
- progressively gets harder either through time (getting more and more tasks) or through levels/map difficulties

## 🤓 Back End Overview
- This game will rely on P2P for server hosting, and for now deciding on using epic games EOS or Nakama for a relay to connect players and have a serverless platform
  - potential for letting players make their own mods and additions to the game
- Maps will have base grid layouts where we can procedurally generate different cities using pre-made buildings and structures
  - roads, greenery, and walkways will be hard coded but the actual buildings are the ones that are going to change
- Players can do basic customization such as suit color, charms etc

## Visuals
- Low poly models that are easy to make and tweak
  - maybe make it physics based (i.e ragdolls, funny physics, etc)
- cell shading to make things lighter on lower end devices
