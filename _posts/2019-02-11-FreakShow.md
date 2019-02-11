---
layout: posthttps://github.com/MCT-master/mct-master.github.io/tree/master/_posts_draft
title: "Freak Show"
date: 2019-02-11 03:59:00 +0200
categories: Audio Programming
author: Sepehr Haghighi
image: /assets/img/freakshow.jpg
excerpt: "As my first experience working with Web Audio API, utilizing JS, HTML and CSS; it was quite a challenge, but a pleasant one that lead to the outcome that I wanted and also broadened my perspective, in regards of my future plans."
---

# Freak Show

## Starting Point
At the start, I have to mention that these seven days, were quite challenging to me. As a person who has done no coding before (only a couple of times before, in the same program), this project has been a little bit hard for me to finish.
The idea of the project is to have a basic interactive experience. There is a Troll picture on the screen and a silly laugh, associated to it. They amount of delay time and size of the troll picture is related to the placement of the mouse and with the curser movement, they shall change as well.

<figure>
<img src="https://github.com/MCT-master/mct-master.github.io/blob/master/assets/img/troll.png" width = "70%" height = "70%" align="center" />
</figure>

With the movement of the mouse, from left to right, the value of the elements - delay time and the size of the picture – increase and also there is a slider placed in the page, in order to control the amount of the delay itself (dry/wet). The whole project is based is utilizing JS for running and also CSS is used in order to make it more appealing.
In here you can observe a presentation of the project:

<video width="640" height="480" controls align="middle">
  <source src="/assets/video/freakshow.mov" type="video/mov">
</video>

## Work Process

### Day 1:
Regarding the first day, I only added a picture and linked it to the mouse position on the page and managed to play a laughing sound effect, but the problem regarding the picture was that the aspect ratio of it wasn’t fixed. I also tried to add a reverb effect to the picture and map the reverb time to the mouse curser as well; but did not succeed in the end of the day.

### Day 2:
In the second day I decided to fix the issues I faced yesterday; but I could not manage to do it. In order to do that different libraries were installed, so they could be a resource in order to create the reverb. Libraries such as p5.js, Tuna and a couple of others which I forgot their name. But none of them basically worked. Also there were several solutions I found online, in order to fix the Aspect Ratio, but couldn’t implement them in the code. I was not present during the presentation of the project in this day. Therefore, Anna did the favor of playing back a short video of the basic idea of my project for me.

### Day 3:
Getting to the third day, with the introduction of the delay code, I thought it would be really nice to implement that effect in the project. Therefore, I put the reverb idea aside and tried to connect the mouse curser placement (variable X for the horizontal placement and variable Y for the vertical one), in order, to the delay time, left and right. Also the effort to fix the ratio didn’t end up to any success in this day. Since I didn’t make any practical progress in day two, I didn’t present the project in the presentation and only showed up the coding and the issues in it.

### Day 4:
In the last day, with the help of Jørgen the Aspect Ratio issue was fixed and the picture was put in the center, top of the screen. I have to mention that in the previous days he was being really helpful regarding troubleshooting and building up the code structure. This was done by dividing the normalized width and height and multiplying it to a defined scale. But still the audio problem didn’t get solved. But with learning how to create different files and connecting them to the index.html file, I managed to create a .js file with all the main codes in them and connect it to the index.html. Also another interesting event that happened in this day was the introduction of CSS to the class. I created a CSS file for the project and by utilizing it i made the background. Afterwards I inserted an slider in the page, and tried to get a sound being played back, with clicking on the Troll picture. But actually at the end of the day didn’t manage to connect the slider to the delay level and make the click playback sound work. Therefor the bright side of my presentation mostly included the visual improvements int he project. Also since it was in the end of the session, I didn’t receive any feedback or questions. The same thing happened to me in the previous day as well, since my project was not developed that much.

### Extra Days :D (Weekend):
Although things didn’t go that much well during the week days, in the weekend with putting a lot of time and effort, with help from a friend of mine - Hamed Kazemi - who is back in Iran, finally the following issues were fixed:

* having the delay being engaged with the mouse movement, by creating a function at the beginning and calling it later on in the code.
* linking the slider to the delay level and creating a fader value field in the page, so the delay level could be observed as well.
* playing the specified sound, while clicking on the picture.
* cleaning up the code and spreading the work load between the various platforms - CSS, JS and HTML; mostly between JS and HTML. For example, instead of everything being happened in JS, the image is being called in HTML and then everything happening to it is being programmed in JS.
* Making the code more organized aesthetically with “Prettier” plugin for Visual Studio Code.

But still one last problem remained. The code needed to create a new buffer node after being stopped. For starting again it needed to create a new node and in order to fix that I used Eigil’s help and finally the project was completed and was working without a flaw.

## Conclusion:
In conclusion, this project was quite challenging for me; but also helped me a lot to figure out how web audio works in practice and made me aware of new possibilities that could come in handy for my future projects. That include both practical aspects and the first ideas regarding those projects. Since the laughing sound used in the project, in combination with the delay and the troll picture, created a really freaky atmosphere; I chose to name the project “Freak Show”.
In the end, I have to thank Anna who tried to help on various issues that happened during this week to me. You can access to the whole project’s codes on this GitHub page:

https://github.com/sepehrhaghighi/Freak-Show

Cheers!
