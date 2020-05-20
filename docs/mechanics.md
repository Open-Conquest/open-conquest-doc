---
id: mechanics
title: Game Mechanics
sidebar_label: Game Mechanics
---

## Gameplay Overview

When a player joins a world they do so as the ruler of kingdom with a single city, their capital. In this city they can construct buildings which are used to produce resources and train army units. Once they build a large enough army they can expand their kingdom's territory by capturing other players' cities or collect enough resources to construct new cities. Either way they can expand their kingdom's territory by increasing number of cities they control. Eventually the kingdom will become so large that it will be impossible to manage. At this point the player can create a hierarchy of lords within their kingdom where each is given control over a set of cities which they can then delegate to their own subordinates and so on. Now the player is a king and the difficulty becomes maintaining good relations with his lords to ensure that they won't secede from the kingdom and claim it for themselves.

## Entities

Only a few major entities are used. But, it'll be difficult to understand the code without knowing how these entities' purposes, relationships, and roles within the game.

Read more about entities [<span class="link">here</span>]().

### Worlds

Instead of Open Conquest being a massive single world, there are many isolated worlds. Each world has its own map, players, etc. When users first sign up they have to choose a world to create a player in. They don't have to stick in this world forever. They can move to a different world whenever but at a cost because it can be abused to evade combat.

Read more about worlds [<span class="link">here</span>]().

### Map

By default a world has a 100x100 hexagonal tile map. Each tile on the map represents one of the following terrains: grassland, forest, mountain, or ocean.

Read more about maps [<span class="link">here</span>]().

### Players

Users join a world as a player. These players are the characters that they play as in the world. Players are a useful entity because users may want to have multiple players in seperate worlds.

Read more about players [<span class="link">here</span>]().

### Cities

Players want to control as many cities as possible because cities are the only way for players to train army units and are the most reliable way of collecting resources. A city's buildings are actually what produce resources and train units, but the productivity of these buildings is dependent on the city's population and terrain. Cities' populations depend in part on the number of tiles a city controls.

Read more about cities [<span class="link">here</span>]().

### Buildings

Buildings serve one of three purposes in a city: producing a resource, training army units, or defending the city.

Read more about buildings [<span class="link">here</span>]().

### Armies

In order to conquer cities players need to successfully attack them with their army. These armies are made up of army units

Read more about armies [<span class="link">here</span>]().

### Kingdoms

Players start as the ruler of the own kingdom made of a single city. Kingdoms are simply a way to organize 

Read more about kingdoms [<span class="link">here</span>]().
