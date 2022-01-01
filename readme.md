# LH-LargeCrappyMaps

A collection of my 100x100 grid maps for FoundryVTT created with DungeonDraft, FoundryVTT and the FoundryVTT modules libWrapper, Levels, Better Roofs,and wall-height.

The maps are system agnostic.

If you are watching me stream on [Twitch](https://www.twitch.tv/lordhaywire) then you can download the files I started working on at the beginning of the stream from the [streaming](https://github.com/lordhaywire/lh-largecrappymaps/tree/streaming) branch.

This repository does not include the DungeonDraft files because you don't need them for FoundryVTT but I have included them in another repository called [dungeondraft-maps](https://github.com/lordhaywire/dungeondraft-maps).  I have not tested that they work with another person.

I also added a [Discord](https://discord.gg/NfVdrnwEQ4) if you want to talk about the maps!

## Dependancy Modules in FoundryVTT

betterroofs

lib-wrapper

wall-height

levels

## Installation

Download the zip file from the repository.

Extract the folder from the zip file and copy it into your modules folder.

The folder must be called lh-largecrappymaps.

Start FoundryVTT and go to Settings > Manage Modules.  Find Lord Haywire's Large Crappy Maps and select it.  If you have the other dependancies already installed it will ask you to enable them.  If you don't have the other dependancies installed then you will need to download them first through Foundry's Add-on Modules tab.

If you need help feel free to ask!  You can find me in my [Discord](https://discord.gg/NfVdrnwEQ4) channel as ClockUniverse.

## Maps

All maps are 100x100 grid squares at 100 pixels and have lighting and roofs.

## Work in Progress Maps (WIP)

Foundry makes it difficult without doing a bunch of work later to move maps around in folders, so I have a hidden folder for testing that you might see in my stream.  It isn't important.

If the map has WIP in front of it then it is a work in progress and may be in any state including completely broken.  The WIP files are included so people can look at what I am doing while I stream.

## Known issues

All the maps take a significant time to load and sometimes the clients connected to the maps require the player to draw a box for the maps to actually show up on their side.  I have no idea why that is.

### Lighting

At some point I am going to make all the lighting the same on all the maps, but I sort of winged it when I first started making maps.  I also haven't decided on which lighting I like the best so whenever that happens I may update the lighting on all the maps.

### Farms North South

Farm land with a road running from the north to the south.

#### Known Issues

Used the built in FoundryVTT roofing.  Should probably change to Better Roofs at some point.  Basically that means tokens can't walk on the roofs.

Need to fix lighting so it flickers.

### Westerm Town East West

An old west style town with an underground level.  There is a road running east west.

#### Known Issues

This map has a shit ton of walls.  Like thousands of walls because of all the trees.  It takes a long while to load.  It isn't really an issue, as it can't be fixed and is just how my maps are.

### Bridge Town North South

A bridge town with an underground level, and a level cut out in the middle with a river running through it.

#### Known Issues

The polygon for Levels has gone crazy and I am not sure how to fix that.  It works great except for sometimes the roofs get a little wonky.  At some point I think I am going to have to manually draw all the polygons for Levels.

#### Lighting

Torch/Lantern Etc Light Color - #e6620a - 60/30

Candle - #e6620a- 10 dim/5 bright

### Thanks

Bailywiki for his tutorial videos about FoundryVTT and Levels.

TheRipper93 for his FoundryVTT modules Levels, Better Roofs, Hurryup etc.

Forgotten Adventures for creating amazing assets.