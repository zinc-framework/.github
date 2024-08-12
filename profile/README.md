ZINC is a cross-platform, 2D game framework for rapidly developing games in C#.  
It prioritizes **immediacy**, **coziness**, and **magic**.  

_NOTE: Zinc isn't officially "launched" yet (you're a little early :))._  

Getting started is as easy as:

```c#
Engine.Boot(() => new Square);
```

Docs/Website/etc. are all being actively worked on. Below are some loose thoughts and notes!  

To read more about the engine, check out this blog post:
[https://afterschool.studio/p/dinghy-year-end-2023](https://afterschool.studio/p/dinghy-year-end-2023)  
To get a sense of the API, [check out the demos repo](https://github.com/zinc-framework/Zinc.Demos/tree/main/Zinc.Demos/Demos).  
To see a sample game built with Zinc: [https://github.com/kkukshtel/7drl-mystery-dungeon-hand](https://github.com/kkukshtel/7drl-mystery-dungeon-hand)  
Read about the development of it on itch: [https://itch.io/t/3553453/mystery-dungeon-hand-balatro-x-shiren](https://itch.io/t/3553453/mystery-dungeon-hand-balatro-x-shiren)  

Other things about Zinc:  
* It is definitively 2D only and makes no concessions at trying to also support 3D.  
* Zinc is unhampered by previous efforts at C# engines. It has no relationship to Monogame/XNA/FNA.  
* It is code only, and will never have an editor (but we give you the tools to build your own).  
* It leverages modern C# and .NET as well as low level C libraries to make it fast.  
* It is backed by an ECS system (Arch) that you can choose to totally ignore by still get the benefits from.
* **Zinc is for people that just want to make games**

Non-comprehensive list of planned and implemented features:
- [x] DearIMGUI Support
- [x] Scenes
- [x] Depot Support
- [x] Hot-reloading code
- [x] ECS Backend (Arch)
- [x] Easy ECS Component APIs
- [x] Sprite Rendering
- [x] Sprite Animation
- [x] Typesafe file access in Res/ folder
- [x] Easings
- [x] Basic Physics
- [x] Simple Collision
- [x] Particles
- [x] Cross-platform
- [ ] Tracy profiler support
- [ ] Controller Input
- [ ] Aesprite File Support
- [ ] LDTK Support
- [ ] Text
- [ ] UI
- [ ] Audio
- [ ] Built-in console/logger
- [ ] Web build targets
- [ ] Custom Shaders
- [ ] Hotreloading Assets

The goal of Zinc is to give you the minimum set of tools that can allow your to quickly build your own games (and engines!). We also act as "glue" between other notable 2D tools, and give you typesafe access to files that come from Aesprite, LDTK, and Depot.  

Zinc is inspired by Heaps, Luxe Engine, Ceramic, HaxeFlixel, and Kaboom.js/Kaplay.  



