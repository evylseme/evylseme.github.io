---
layout: my_post
title: Interactive assignment
date:   2017-11-12 18:40:38 +1300
categories: projects
---

**Musical application**
During this assignment you will design and produce an application that allows the user to make music in a novel way.

**Minimum requirements**

+ Some form of animated graphics
+ User interaction to construct sound combinations
+ Sounds that are triggered in some way
+ Basic instructions included somehow

## Brainstorming

+ Do something with colors, inspired by Pocahontas “can you paint with all the colors of the wind”
+ Use 3D model helmet, get some weapons and start hitting it. With every different weapon it will make a different sound. 
+ Think less instrument and more musical: make 1 scene of a fairy tale and let the user define the story. 

## Fairy tale

Famous fairy tales are usually about a villain, a prince and a princess. I’d like that traditional feel, also because my 3D model is already in a similar theme. I want to go so far back to traditional fairy tales to say we have a Dragon and a knight fighting over a princess. But I decided to add a support character to make things more interesting. This way I have 2 characters who are offensive and 1 defensive. 
So let me clarify the idea here: 
What the user will see is a play where he/she is the director. User will get 3 options (as there are 3 characters), all he can do is click on the next option. In other words, the user decides the order in which a character gets to do something. BUT! Every choice comes with a consequence. This can end very bad or very good. It can lead to the dragon killing everyone, so beware. 

![screenshot]({{site.url}}\assets\interactivity\screenshots\IconicPartyRedDragon.jpg)

source: [boingboing.net](https://boingboing.net/2014/07/21/an-exclusive-look-at-the-new-d.html)

### Story 

The story is fairly simple and standard. The knight is send to defeat the dragon to bring back the princess. The knight brings a paladin/priestess with healing abilities for support in the dangerous battle. 

### Characters

**Knight:** 
+ Mission: ready to safe the princess. 
+ Has no intention of talking
+ Offensive character, believes in fighting
+ Close combat with great sword

**Dragon:**
+ Mission: protect its property and home
+ In this world dragons cannot speak, but they are noble creatures still. 
+ Seen by the world as hostile. 
+ Offensive character, the ways of animals
+ Both close and long range combat with fire, claws and teeth.

**Support:**
+ Mission: Help the knight in his mission
+ Has all intention to use peaceful ways to retrieve the princess.
+ Defensive character, believes in keeping the peace.
+ Long range combat with magic

## Mapped storylines
**SPOILER ALERT**

The next images show the choices a user can make and what the result would be!!!

![screenshot]({{site.url}}\assets\interactivity\screenshots\storyline_DragonFirst.jpg)

![screenshot]({{site.url}}\assets\interactivity\screenshots\storyline_KnightFirst.jpg)

![screenshot]({{site.url}}\assets\interactivity\screenshots\storyline_SupportFirst.jpg)

  <br>

Now to make it easier on coding later I gathered all possible actions per character: 

![screenshot]({{site.url}}\assets\interactivity\screenshots\character_actions.jpg)

## Design

Since I’m working with old fashioned fairy tales and musicals, what better than to make the environment looking like a theatre. It’ll instantly show it’s about a story. Having a theatre with the red curtains and wooden stage, also means the décor will look like carton that is painted on. Other than that, the characters will be 3D, because what’s a theatre without actors. However the original idea was to build the characters as well as 2D art works, and the animation would be minimal. It would be like reading a coming, one second the characters are posing as if they want to sit, the other they are posing as if they want to laugh (for example). This way I would putting more elements of old fashion in my little game. But I do not have an artist at my disposal who can build the 3 characters in the few poses I need from the right angles. 

![screenshot]({{site.url}}\assets\interactivity\screenshots\design_theatre.jpg)

## Tooling

Unity, this is a free tool, famous for building games. It will give me the opportunity to easily find assets like the characters and the environment which will save time and effort that is not necessary. It also helps that I am already familiar with the program and understand it’s capabilities.

<br>

Special research has been conducted to find out if it can publish the game on a website, which is possible: 
+ [Building with unity webplayer](https://unity3d.com/learn/tutorials/projects/space-shooter-tutorial/building-game)
+ [Building with WebGL (recommended by Unity instead of unity webplayer)](https://docs.unity3d.com/Manual/webgl-building.html?_ga=2.44681324.938216090.1510362172-1831751997.1510362172 )

Assets can be found for free at [Unity asset store](https://www.assetstore.unity3d.com/en/) and [Free3d.com](https://free3d.com/)

## Execution

During the execution I was happy to have some knowledge of how to build the environment in Unity. So the temporary base was quickly done. I say temporary because this is not as designed, it's simply a first draft to get the first parts to work. 

![screenshot]({{site.url}}\assets\interactivity\screenshots\screenshot_halfway.jpg)

The first challange came with the assets (dragon, knight and support). The knight was easy. Found in the Unity Asset store. It came with a nice look and was therefore good enough. The supporter was a bit more difficult and was found on the free3d website. The textures came with it, but it didn't fully work. Half her body is not colored. Unfortunately there is no time to fix that. Last, the dragon was found also on the free3d website, and thank god the texture worked. This was also the only character that included animation! Which made that part slightly easier. Trying to animate characters like that on your own is quite the pain I learned! And I'm grasping at a too high level with that idea. 
I did look into easier ways to animate and a friend suggested: [Mixamo](https://www.mixamo.com/). But as that turned out, it didn't work either. It either didn't load in the dragon or it turned the knight upside down.

So if I can't do that yet, then let's look at the requirements: 
+ something animated 
+ something interective for the user
+ something that produces sound 
+ the tutorial

Well for now I can put all in the tutorial. Plus the tutorial is the introduction of the game. I wanted it to sound a bit story/theatre like.

![screenshot]({{site.url}}\assets\interactivity\screenshots\tutorial_build.jpg)

So: 

"Ladies and gentlemen! I present to you, the first draft of the game!"

## Result

[Click here to see the game]({{site.url}}\assets\interactivity\releaseBuild\index.html)

<br>
