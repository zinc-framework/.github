ZINC is a cross-platform, 2D game framework for rapidly developing games in C#. It prioritizes immediacy, coziness, and magic.

Getting started is as easy as:

```c#
Engine.Boot(() => new Square);
```

Docs/Website/etc. are all being actively worked on (you're a little early :)).  
To read more about the engine, check out this blog post:
[https://afterschool.studio/p/dinghy-year-end-2023](https://afterschool.studio/p/dinghy-year-end-2023)

Other things about Zinc:  
* Zinc is unhampered by previous efforts at C# engines. It has no relationship to Monogame/XNA/FNA.  
* It is definitively 2D only and makes no concessions at trying to also support 3D.  
* It is code only, and will never have an editor (but we give you the tools to build your own).  
* It leverages modern C# and .NET as well as low level C libraries to make it fast.  
* It is backed by an ECS system (Arch) that you can choose to totally ignore by still get the benefits from.
* **Zinc is for people that just want to make games**

The goal of Zinc is to give you the minimum set of tools that can allow your to quickly build your own games (and engines!). We also act as "glue" between other notable 2D tools, and give you typesafe access to files that come from Aesprite, LDTK, and Depot.  

Zinc is inspired by Heaps, Luxe Engine, Ceramic, HaxeFlixel, and Kaboom.js/Kaplay.  

More soon!
