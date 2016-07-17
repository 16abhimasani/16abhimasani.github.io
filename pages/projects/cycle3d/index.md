---
layout: page
title: Cycle3D
---

<figure class="hero">
	<div class="media media-1">
		<img src="/assets/images/cycle3d/banner.png">
	</div>
</figure>

Cycle is an open source 3D printing project focused on creating a new type of 3D printer that can essentially recycle its own prints and utilize other recyclable plastics like PET or HDPE which is most often found in plastic containers. The project originally started as simple machine that can create filament out of ground up plastic but has since evolved into an "all-in-one" type of printer that can directly intake granular plastic instead of filament. Because of this concept, the two major components of the Cycle printer is the Grinder and Extruder with each partaking in the recycling process.

## Grinder

<figure class="hero">
	<div class="media media-1">
		<img src="/assets/images/cycle3d/grinder.svg">
	</div>
</figure>

The Grinder works by first crushing and tearing plastic with the primary rollers. Next the shards are dropped into the secondary shredders where the high speed and sharp blades cut the plastic to small pieces. The filter below, fitted with 2 mm holes, allows oversized pieces to be kicked back up for more shredding. Overall the grinding part of Cycle printer is the most mechanically difficult because proper extrusion requires uniform piece size and shape. The filter part of this design minimizes bad pieces but overall the mechanical aspect of this design is still a work in progress.

## Extruder

<figure class="hero">
	<div class="media media-1">
		<img src="/assets/images/cycle3d/extruder.svg">
	</div>
</figure>

The Extruder works by intaking granulated plastic and passing it down the chamber via an Auger bit. This chamber is specifically designed to have a longer melt zone for efficient flow rate and retraction. The Auger bit allows the granular plastic to be carried down by the stepper motors in the extruder head. This method also allows simple retraction identical to normal extruder by simply reversing the motor to pull material back up.

>The future of 3D printing can be summarized by the progression of recyclable material technology

## Grinder

An overview of the Grinder's technical specification, design features, and build log.

### Grinder Assembly

#### Assembly and Cross Section

<figure class="hero">
	<div class="media media-1">
		<img src="/assets/images/cycle3d/grinderassembly.png">
	</div>
</figure>

The goal with the grinder was to design a compact grinding solution that could reduce big milk jugs or small scrap plastic to 2mm granular pieces. This size is optimal for the extruder to handle at reasonable torque. For this reason I knew that simply throwing everything into a blender wasn’t going to work. I decided to design the grinder to use a 2 step grinding process. The primary grinder section at the top intakes raw plastic (like water bottles) and shreds them at slow speeds, essentially tearing the material into manageable chunks. The secondary shredders are the second step of this process where the large chunks are reduced to smaller pieces through multiple shredders. The filter at the bottom allows pieces that are not small enough to be kicked back up into the shredders until uniform size is achieved. This vertical grinding process in theory generates the best results but an ideal grinder (cheap and simple) would only have 1 stage shredding designed in such a way that thin walled plastic can be chewed up right away. 
