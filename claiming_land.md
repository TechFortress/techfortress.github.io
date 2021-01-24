---
layout: page
title: Claiming land
permalink: /claiming
---

<head>
    <style>
        .iframe-container 
        {
            overflow: hidden;
            padding-top: 56.25%;
            position: relative;
        }
        .iframe-container iframe 
        {
          border: 0;
          height: 100%;
          left: 0;
          position: absolute;
          top: 0;
          width: 100%;
        }
    </style>
 </head>

# How to claim land

## Claiming tools

- Wooden shovel
- Stick

This video shows how to create and resize claims using the shovel. Depending on circumstances, you might find this an easier way to manage claims than using commands:

<div class="iframe-container"><iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/9aAiFcOx6iE" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
 
## Listing and Deleting claims

- **/listclaims** - Lists all your claims and the amount of claim blocks available to you.
- **/abandonclaim** - Abandons the claim you're standing in.
- **/abandonallclaims** - Abandons all claims you own.

## Giving claim trust to other players

- **/trust `player`** - gives `player` permission to build, destroy, etc, and everything in /accesstrust and /containertrust
- **/accesstrust `player`** - gives `player` permission to use doors, levers, buttons, fence gates, etc.
- **/containertrust `player`** - gives `player` permission to open chests and other containers, and perform farming tasks, such as milking cows, killing and breeding animals, destroying and planting crops, etc, and everything in /accesstrust
- **/permissiontrust `player`** - gives `player` permission to /trust and /untrust other players.

> You can use `public` in place of `player` to give that trust to all players. Generally useful for /accesstrust to allow others to open doors and push buttons, but preventing them from killing animals or breaking blocks.

## Managing the claim trust list

- **/trustlist** - Lists players you've trusted to the claim you're standing in.
- **/untrust `player`** - Removes player from your trust list inside the claim. To remove the player from all of your claims, stand outside the claim when executing the command.
- **/untrust all** - Removes everyone from your trust list for that claim.
