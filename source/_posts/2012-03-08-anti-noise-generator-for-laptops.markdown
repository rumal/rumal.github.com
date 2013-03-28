---
comments: true
date: 2012-03-08 12:40:01
layout: post
slug: anti-noise-generator-for-laptops
title: Anti noise generator for laptops
categories:
- Desktop Applications
- My Ideas
- Under Development

img : anti-noice.jpg
des : Software that cancel out the noise in the environment by using the mic input and return the inverse pattern to the speaker.
---

##Background
I was wondering whether I can create a software to reduce sounds in the environment. Ideally when I run the application it should remove the noise in the environment. Simply cancel of the noise or sounds in the environment. I was thinking of the same technology as the noise cancelling head phones. As I know what they do in simple terms is they get the noise in the environment and subtract it from the music we are listening to. So when we hear the music with the noise, the subtracted part is added and we only hear the music.
Well I was thinking of doing it on the machine. Instead of subtracting it from a music if we can simply generate a inverse noise signal to the original noise they would cancel out and we will be having a calm environment.Since most laptops have microphones inbuilt we can get the surrounding noise from that. What we need is to then invert it and output it from the speaker. If we are playing a music we could subtract the noise from the music and play it on the speaker so as I mentioned when we listen we will hear only the music we played.

We could also write a driver which is just a wrapper to the original audio hardware to implement this functionality and the user can select the driver when they want. I searched on the internet but could not find a similar software for a machine or a mobile phone. I was wondering what is the technological barrier in-between. Can we create negative amplitude waves from speakers or from any other devices?  I'm pretty sure this might be a barrier when implementing. If this is not possible we can not cancel out the noise. But we can change the unpleasant noise to some tone we like. This can be done by adding some other wave form to the noise. In any case we can create that noise cancellation when we are playing a music or a song on laptop as we have a final wave and what we need is to subtract the noise from the music we are playing
