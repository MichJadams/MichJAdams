# Hey, I'm Michaela! 

I'm a software Engineer currently living in DC 🏛️. I enjoy playing games (Currently Gloomhaven, Disco Elysium and Crusader Kings III), reading sci-fi and fantasy and riding my bike all around town (also on weightlifting!). I'm teaching myself C++ and Arabic in my free time. 

![GitHub Streak](https://streak-stats.demolab.com/?user=michjadams&theme=default)

## Projects 📦

### Completing Programming Principles and Practice With C++ by Bjarne Stroustrup 

I'm doing all the exercises of the entire book. One of the beginning ones was baking myself bluberry muffins. 

### Second Script (![repo here](https://github.com/MichJadams/ArabicTyping)) 
No tutorials this time! Just stumbling around trying to make a little game to help me learn to type in Arabic. I'm using Godot and GDScript. As it stands the game starts and allows a player to type in characters. If the chracter matches it turns green, if it does not the character changes and turns red. 

Lastest Progress: 
2/22/2024 I added a background image. I had to edit the image myself in Krita, so it's a bit messy. But I like this general color scape. I think I need one more color in the mix besides the browns and the blue. But I really like the dithering. I've also added the ability to add individual words and translations (rather than just upload from a csv). 
![image](https://github.com/MichJadams/MichJAdams/assets/30957743/ba83f9c4-c74a-4248-9492-1ddf36da1f2c)


2/14/2024 I've been messing around with the main menu and the design. I really like this brown and light blue combination and I got a new font in the mix. ![image](https://github.com/MichJadams/MichJAdams/assets/30957743/47b71661-4ba5-4e9c-86e3-a30e19e5f31d)
![Pasted image 20240214175813](https://github.com/MichJadams/MichJAdams/assets/30957743/d2834bad-9cba-407f-a414-e8068e90dbca)


2/8/2024 I just added the fastest and dirtest "add a single card" page. I mostly added this feature because I genuinly wanted it for drilling pronunciation for practice myself. The workflow of adding a letter or a letter and an accent and then going to the "simple queue" page and loading them up to drill is very satisfying. 
![image](https://github.com/MichJadams/MichJAdams/assets/30957743/4c64f3e8-0d97-4aab-8afd-803625fb5dc9)
![image](https://github.com/MichJadams/MichJAdams/assets/30957743/e8f8c792-7c00-463b-9802-7ab525c41ede)

2/3/2024 I'm really excited by these new vocabulary cards! This is the simple queue mode which allows you to select 10 specific cards and drill those infinately. I'm still working on the layout for this settings page.
![image](https://github.com/MichJadams/MichJAdams/assets/30957743/f7b132ba-a37e-4a62-b335-1292102401aa)

OLDER:
I rewrote how all the vocabulary words are being stored, but that is honestly a pretty boring visual. So instead take a look at some main menu redesigns 
![image](https://github.com/MichJadams/MichJAdams/assets/30957743/579f984e-3268-4203-8753-79b1b9471b1a)

I have done some visual clean up, and figured out how to properly drag and drop the cards around! Before I could only drop the cards on the gray background pannel. 
![Arabetter_08_drag_drop](https://github.com/MichJadams/MichJAdams/assets/30957743/5913f8d1-ca97-49b4-9631-bd05a2ea17ff)

This is the visulization of the Leitner System that is the underlying algorithm used to select which words will appear in a given study session
![Arabetter_06](https://github.com/MichJadams/MichJAdams/assets/30957743/2bd4e554-0695-4183-9db3-3748c0209db0)

This is a general tour of the new feel of the application
![Arabetter_05_loading](https://github.com/MichJadams/MichJAdams/assets/30957743/14f4aee1-9f55-4969-8f65-839d4b0c9e51)

![Arabetter_04](https://github.com/MichJadams/MichJAdams/assets/30957743/dd65fc4b-35d8-4545-a03c-dde7c8fc0d1e)

![Arabetter_03](https://github.com/MichJadams/MichJAdams/assets/30957743/e02389b0-99a1-4e65-9cbc-0e0126c652a4)

Bare bones beginning
![Arabetter_01](https://github.com/MichJadams/MichJAdams/assets/30957743/2d3e5886-dc6c-4c1c-a10d-9734cebaffeb)
#### Future Features 
 - [ x] Load in vocabulary (currently set to just a single set of words)
 - [ x] Record player score
 - [x ] Use a third party API to pull audio of word pronunciation
 - [ ] Give the option to change the word to English after it is typed
 - [ ] Remove duplicate words when user uploads multiple copies
 - [ ] cache the .mp3 file for each word pronunciation as a resource associated with that word so you don't have to fetch it every time (and also decreases chance of being blocked by reverso)
 - [ ] Create map of code
 - [ ] Figure out why the back button from "settings" stalls/hangs
 - [ ] Write a little explanation of how I got the verbal pronunciation of each word to load 
       
### Ray Tracer 🎨
I am following a test-first guide to writing a ray tracer. 
This picture is really faint, but there is a precious red parabola for those really looking close.
I have decided to do it in C#! 
https://github.com/MichJadams/RayTracingBook

![Ray Tracing Example01](RayTracingExample01.png)

Look at these beautiful tests 🧪
![Ray Tracing Tests](RayTracingTests.png)


### Unity Course 🎒
Working through a course to learn Unity! Currently I've created a number guessing game that 'barrows' heavily from GLAdUS (from Portal). 
And now working on a breakout game.
With my breakout game I'm working on creating interesting blocks that fall, or react to physics. 
I'm also adding interesting ball effects, such as getting larger. 

![Boulder Smash Game Play](BoulderSmashGamePlay.gif)

Example of boulder smash game play as of 6-8-2021

 - [x] Ball gets bigger every 5 bounces
 - [x] Player death and restart game loop is complete 
 - [x] Player score is kept
 - [x] Certain blocks fall when hit 
 - [ ] The paddle works as a sea-saw, allowing player to have two balls that bounce one at a time
 - [ ] Create custom assets 

### Forgot Password 🤔
A little game a friend came up with where the whole thing is to guess passwords based on hints. This was a proof of concept I made and deployed to surprise him. There isn't any content yet, just a basically game loop and win condition.
https://forgotpassword20210419165204.azurewebsites.net/
![Forgot Password Example](ForgotPasswordExample.png)

### Battle Bits 🛳
I made this game when I was first starting out, and I still enjoy it's concept and design.
![Battle Bits Pic](battleBitsPic.png)

## Languages 
- C# ⭐⭐⭐⭐⭐
- TypeScript/JavaScript ⭐⭐⭐⭐
- Python ⭐⭐⭐⭐
- SQL ⭐⭐
- Rust ⭐

## Tools 🔨
- Git. And Github. 
- Visual Studio. And Visual Studio Code
- Jira
- Microsoft Sequel Server Studio 

## Concepts 💭
- Unit Testing, Integration Testing (Mostly in C#, once or twice with selenium)
- Agile Methodologies (Card Creation, Point Estimation, Sprint Planning)
- Code Reviews (C#, TypeScript)
