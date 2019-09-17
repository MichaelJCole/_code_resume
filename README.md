# Michael Cole, Technologist

Hi, my name is Michael and I'm a technologist.  

There is no greater feeling than speaking a new reality into existence - that is the true power of software engineering.  

As a freelancer, I've specialized in helping small/medium sized business get from and idea to a beta.  My <a href="https://powma.com" target="_blank">portfolio site</a> includes some examples of that work.

<a href="https://stackoverflow.com/users/1483977/michael-cole?tab=profile" target="_blank">StackOverflow</a> and <a href="https://www.toptal.com/#expect-adept-developers" target="_blank">Toptal</a> claim I'm in the **top 3% of software developers**.  Who am I to humble-brag a disagreement?

Below are examples of **technology experiments**, **personal projects**, and **speaker decks** I've created explore, share, and practice creating technology.  

> These are not polished "products", but experiments I took as far as was fun.  
> 
> Like all art, code is never finished, it must be  abandoned.

## WebVR, Web Workers, and WebAssembly

<iframe src="https://michaeljcole.github.io/n-body-wasm-canvas/" style="height: 80vh; width: 80vw"></iframe>

## Speaking Decks

### Web Workers
[Web Workers, Service Workers, and PWAs](https://slides.com/michaelcole/deck-1-6-5/live#/) introduces Web Workers (used in the demos above) then shows how Service Workers are the crucial technology that enables “off-line” PWA's.

### MapReduce

[MapReduce Talk Slides](https://slides.com/michaelcole/deck-1-6/live#/) This is a great talk on MapReduce for non-coder "data scientist" groups.  It covers MapReduce starting with JavaScript for the fundamentals, and moves to MongoDB + Wikipedia’s dataset for the fun.

The beginning slides show “white cards” and are an interactive experience getting an audience to create their own dataset (on 3x5 cards), then MapReduce it to answer questions. From there, we build some examples using JavaScript, then look at MapReducing the Wikipedia dataset using MongoDB.

## Quathers - Full-stack Starter Project
Tech:  Vue.js, Quasar, Material Design, FeathersJS, Node, Express, MongoDB, Docker, Authentication

<img src="https://github.com/MichaelJCole/Quathers/raw/master/screenshot.png" alt="Screenshot" style="width: 500px; float: right"/>

Quathers is a Full-stack Starter Project [source code MIT](https://github.com/MichaelJCole/Quathers) that integrates Quasar and Feathers.  It includes:

- Quasar Front-End Framework:
  - Quasar = VueJS + Material Design + PWA/SSR + Electron (desktop packaging) + Cordoba (mobile packaging)
  - It a fairly complete opensource framework with an excellent component palette
  - Includes tooling for building desktop apps, mobile apps, and PWA's.

- FeathersJS
  - Simple service oriented backend framework
  - Multiple transport options (REST, Socket.io, Primus)

Tech stacks change, and I could no longer recommend MeteorJS to clients.  While looking for a new tech stack, I came across Quasar and Feathers and wanted to see what was missing for a full-stack framework.

Quasar is a great front-end framework with tooling for SPA, static sites, server-side render, and build tooling for desktop (Electron) and mobile.  




## Web Assembly
I wanted to see how far I could push browser-based computing, and this was an experiment in using Web Assembly.

Web Assembly is a standard for writing and compiling non-JS languages into JS.

The technology is almost universally available in evergreen browsers, but can be clunky to work with.

Here is an implementation of the “3-body problem” in C using Web Assembly and the Canvas API for the front-end.

WebVR (Virtual Reality)
VR is the next iPhone.  Not the iPhone X, but the original.  The thing that created the whole “mobile” world around us.  VR is a 10x emotional experience and a completely new entertainment art form.  

All previous forms of art have a “4th wall” that separates the art and artist from the viewer.  And all those “renegade” art-forms that “break the 4th wall” are a novelty reaction to the 4th wall.

VR has no 4th wall.  And if you try to make one, your players will want to puke.  Literally from VR sickness.

If you force move the player, they will get VR sickness.  
If you let the player move themselves to forcefully, they will get VR sickness.
If you develop in VR, you will get VR sickness.
If you force a player to watch a full-screen movie, they will get VR sickness.  You have to create a stage where they can look around.

VR is a game changer, buckle up! 

For funsies, here is an implementation of the 3-body problem using WebAssembly and WebVR.

These are interesting experiments, and since then, I’ve been focusing on using the Unreal Engine to create content for the Oculus Quest (Android) and Google Cardboard (Android).
Gamification
While not a tech in itself, here are a series of experiments I created while learning Vuejs and Phaser.io (a popular HTML game engine).

My take-away was that unless the project needs a “game loop”, gamification can be accomplished without Phaser.io.

