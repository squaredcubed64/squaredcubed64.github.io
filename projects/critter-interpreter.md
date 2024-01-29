---
layout: single
title: "Critter Interpreter"
---

I made an interpreter for the "Critter" language, which controls virtual Critters on a grid. Each Critter has their own source code, which is written in an assembly-like language.

For example, this is the source code for a simple Critter called a "Roamer."

```
1. ifenemy 0 7
2. ifempty 0 5
3. left
4. go 1
5. hop
6. go 1
7. eat
8. go 1
```

Each turn, the Roamer checks if there is an enemy in front of it. If there is, it eats the enemy.

If not, it checks if the tile in front of it is empty. If it is, it hops (moves forward). If not, it turns left.

Here is a video showing 30 Roamers (purple) battling against 30 "Food" (pink):  
{% include video id="CwMMKeNf33s" provider="youtube" %}
<small>*\*Note that I made the interpreter for the Critter language, not the GUI.*</small>

In this video, I've added an additional 30 of "SmartRoverv2" (orange):
{% include video id="wrbHJVj_efU" provider="youtube" %}
<small>*\*Note that I made the interpreter for the Critter language, not the GUI.*</small>
