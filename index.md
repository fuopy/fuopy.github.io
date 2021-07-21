# About me

Hey, I'm fuopy! My mission is to bring traditional video games to Social VR.

I hope to set the functional expectations for users of Social VR platforms. By this I mean that I want to set an example for both player and platform developers of what traditional video games can look like in Social VR.

I'm aiming to build the stepping stones so it's easier to see what the future can look like for players, content developers and platform developers. This means I'm:
- Porting games to VRChat so they can be played in worlds and avatars,
- Releasing and supporting open source code so others can make games,
- Creating original games of my own for VRChat.

Right now I'm currently in the porting phase of my effort. I'm releasing all my code for free in the hopes that it will help others to learn to write their own games. I'm starting off with VRChat content, but down the line I expect to port games to other Social VR platforms as well.

If you want to reach out to me, whether its questions, suggestions, or just to chat, please don't hesitate to add me as a friend on VRChat. My name is "fuopy!" Otherwise you can reach me publicly on twitter, @fuopy.

# Gaming in Social VR

Social VR is already amazing today, but there's still some types of experiences that aren't readily available. I've chosen to focus on bringing what I call "traditional video games" (games that you play on a TV screen or monitor) to Social VR platforms. I want to recreate what I used to do in the old days--come home from work, throw Mega Dude II on the screen, put a casette in the boom box and take turns playing through levels with my friends!

My inspiration for this effort starts with the Arduboy. I want to share my love of that game system with everyone in VRChat by making a game store which featured lots of community-made games. Arduboy is my favorite platform to write and prototype games for, and it has a pretty good number of good MIT-licensed games available. So I'm starting off with porting these games to HLSL shader code to run in VRChat.

In the process of porting GLOVE, my first Arduboy game, I've experienced the joy of seeing people play my game for the first time. That experience made me realize this project is also beneficial to game developers. I realized that there's a bit more I can do than just Arduboy. So now I'm hoping to build an experience baseline, so that users of Social VR come to expect traditional video games to be availble in all of Social VR. I'm also hoping to inspire game developers to try making their own that run in Social VR by (attempting) to show that it's not too bad writing games in HLSL. :)

## Other benefits of Social VR

I believe Social VR offers huge potential for those who are prototyping games as well as products in general. Instead of spending money, you can create your prototype product to exist in Social VR. Targeting a platform like VRChat for your prototype even allows you to leverage an existing large playerbase.

Social VR is also amazing for digital artists. If you create 3D models, wild shaders, or are just interested in level design, you don't need to make an entire game. Games like VRChat specifically allow the use of real tools like Blender and Unity to create content, so you can build and showcase real skills. Offline, I'm aiming to inspire creative people to take the plunge into Social VR and see the benefits for themselves.

## The Layers of Social VR

Fundamentally I think that we have a lot of great technology already made, and all we need to do now is glue it together. I see Social VR as a set of layers. At the bottom, we have the social or avatar layer where players talk to each other directly. VRChat and NeosVR fit into this model. On top of that are auxiliary experiences. Right now there's lots of discussion and thought about "creating a metaverse." The way I see it, we've had "the metaverse" as soon as semaphore towers were created. The experience of using Discord to bridge the experience not provided by VRChat is part of "the metaverse." Tweeting about a VRChat concert is part of "the metaverse" experience.

So the way I see it, we should leverage a whole bunch of awesome code and experiences that already exist, and make them work with Social VR!

Here's one example: App switching. If we have a way of switching apps while preserving a social context, we're good! A project I'm looking into is using something like [AardvarkXR](https://github.com/aardvarkxr/aardvark) to prototype portal-dropping in an overlay. Users who have the portal layer installed will be able to see them. Aardvark is an overlay that lets you create gadgets using React.

Another example would be a [parsec](https://parsec.app/) layer. Parsec is fast enough to beat out the native netcode of some fighting games! Maybe we don't need to burden the author of the Social VR application and instead leave this specialized functionality to another layer?

Or take something like [jacktrip](https://www.jacktrip.org/), which is a low-latency way for musicians to perform with one another over the internet. It's another highly-technical specialized solution that may not be appropriate for a SocialVR platform to implement on its own.

Despite all this about layers, I still think creating content in-platform is important. Right now VRChat offers free hosting for so much user content. It has a large playerbase, and users don't need to install anything special to go between experiences. So going forward, the majority of my time is still going to be spent directly on making it easier to play traditional video game in-platform.

# My relevant released projects so far, chronologically.

## GLOVE (Arduboy, 2015)
[code](https://github.com/fuopy/glove) - [release thread](https://community.arduboy.com/t/glove-a-lighter-softer-cozier-gauntlet/214) - [mobygames](https://www.mobygames.com/game/arduboy/glove) - [trailer](https://www.youtube.com/watch?v=zUYfu6g3Nj0)

I wrote GLOVE for the Arduboy in 2015. It was my first Arduboy project and it was a ton of fun creating the game on an early devkit unit of the Arduboy. In one week I created a game with a design based on Gauntlet. I created a level compression format, editor and shipped a game with 30 levels! It was a breath of fresh air during a particularly trying time.

## Virus LQP-79 (Arduboy, 2016)
[code](https://github.com/Team-ARG-Museum/ID-40-VIRUS-LQP-79) - [release thread](https://community.arduboy.com/t/virus-lqp-79-eighth-team-a-r-g-game/1646) - [mobygames](https://www.mobygames.com/game/arduboy/virus-lqp-79) - [archived home page](https://web.archive.org/web/20170126011341/http://www.team-arg.org/vlqp-manual.html) - [trailer](https://www.youtube.com/watch?v=zW-nlaZIMIU)

For the 9th Arduino-Jam, J03RI of Team a.r.g suggested making a zombie game in #arduboy on freenode. I thought that sounded super fun and wanted to be a part of it! In just a couple days, we had a neat game. More work was done on the game by other members of Team a.r.g during the time following the jam. The game proved to be popular, there's even a neat [fan port to MSX!](https://github.com/Team-ARG-Museum/ID-40-VIRUS-LQP-79)

## ABAsm (Arduboy, 2016)
[code](https://github.com/fuopy/ABasm) - [release thread](https://community.arduboy.com/t/abasm-dp1-program-the-arduboy-on-the-arduboy/2608) - [trailer](https://twitter.com/fuopy/status/745530961450827776)

ABAsm is a little VM for creating games for the Arduboy, on the Arduboy! Arduboy is based on a harvard architecture where you can't directly execute RAM, but I wasn't about to let this stop me. I loved the idea of creating games for the Arduboy, on the Arduboy! So I created a little code editor inspired by assembly programming and Sublime Text to let people do that! It's a very simple scheme that only allows for programs of up to 128 opcodes, but I managed to demonstrate writing simple games like snake into it! I was working on a second take on it with a much more sophisticated scheme prior to work but ended up not having time to complete it.

## Work (2017 - 2021)
I had a job and worked full time on some low-level C++ code. I was also working on stuff that runs in a web page! I learned a lot of awesome things and had the privelege of working on some challenging projects with great people!

Aside from work, I have many unpublished projects I worked on for fun in my spare time during these years. I also have a lot of Arduboy projects that I want to start working on again. Maybe some day I'll put them online!

## GLOVE-SHADER (HLSL and VRChat, 2021)
[code](https://github.com/fuopy/glove-shader) - [release thread (vrchat)](https://ask.vrchat.com/t/glove-arduboy-shader-game-engine/5934) - [release thread (arduboy)](https://community.arduboy.com/t/arduboy-in-unity-vrchat-shader/9735) - [vrchat world link](https://vrchat.com/home/world/wrld_3b516a37-2996-4b81-afbc-c1ce535f0879) - [community meetup demonstration](https://www.youtube.com/watch?v=Y-ML3wdqBaA&t=6552s) - [trailer](https://twitter.com/fuopy/status/1387813350155821061)

In March 2021 I ported GLOVE to HLSL shader code. I knew nothing about writing shaders beforehand, but during a weeklong vacation I managed to go from nothing to making a fully playable game in HLSL shader code! Special thanks to llealloo for introducing me to shader development, and to merlin and other helpful folks in his shader discord! After all that, I demoed the game at the community meetup. A month or so later, I did a postmortem panel about how I created the game during TLX, a VRC Prefabs developer event.

## GLOVE-EDIT (Love2D, 2015 and 2021)
[code](https://github.com/fuopy/glove-edit) - [release thread](https://community.arduboy.com/t/glove-a-lighter-softer-cozier-gauntlet/214/16) - [trailer](https://twitter.com/fuopy/status/1388961945496129538)

In the theme of wanting to make traditional video game development more accessible in Social VR, I dug up my level editor and added an option for outputting code that works in the shader version of GLOVE.

## TLX (Presentation, 2021)
[watch video](https://tlx.dev/talks/TLX2021-05/Shader%20Game%20Development)

In May, I gave a postmortem presentation on the making of my GLOVE port to HLSL shader code. The release of GLOVE-SHADER helped me meet a lot of new friends. And thanks to the encouragement of my friends, I decided to give a TLX talk! I used the talk to share what I learned, and hopefully use it as a way of inspiring other developers to make games, too!

## VIRUS LQP-SHADER (HLSL and VRChat, 2021)
[code](https://github.com/fuopy/glove-shader) - [vrchat world link](https://vrchat.com/home/world/wrld_6c2a3363-a34f-4765-8a61-6f92f4a299b3) - [community meetup demonstration](https://www.youtube.com/watch?v=Ik-HC5NGeQc&t=3379s) - [trailer](https://twitter.com/fuopy/status/1410314131425533952)

Building off GLOVE-SHADER, I started my second Arduboy port. During GLOVE-SHADER's development, I wanted to demonstrate that it was somewhat straightforward to copy-paste Arduboy games with simple logic into HLSL and change syntax to make it work. I took a different approach with VIRUS LQP-79. Instead, I wrote it in a way that feels closer to HLSL than the original code. I still worked through the logic line-by-line. But I made the game more "shader-y" by packing two-dimensional values in int2 and things like that. I demoed it at the community meetup, and people seemed to like it!
