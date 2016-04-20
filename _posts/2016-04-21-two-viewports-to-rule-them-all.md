---
title: Two viewports to rule them all
---


The amount of available screen sizes is exploding. That is why we need responsive design. But what if I told you you only needed two sizes? Impossible, I hear you think. But you may be wrong. Hear me out, because this technique can potentially save you a huge amount of time (and/or money).&nbsp;

I have been experimenting with responsive web design &nbsp;a lot lately. This is mainly due to my side project called 'Without Coding'. In this project I give graphic designers a photoshop-like canvas for building websites. This canvas is based on absolute positioning, which is why normal responsive techniques are unfit. While trying to fix this problem, I came up with the idea of 'fixed viewports' (as opposed to fluid responsiveness).

The concept of 'fixed viewports' is based on the premise that all screens have viewport scaling, unless they have a certain minimum width. This minimum width is what we call the 'desktop width'. This is nowadays about 1200 pixels. This 'desktop width' can be shown on tablets through viewport scaling. Using this width on a phone, would result in an illegible website. Therefore we need a second width, the 'phone width'. Using 400 pixels for this width works best for me.

What I do, is that I build for each of these sizes a fixed-width website. I do this using conditional CSS. I start with 1200 pixels version and I use Javascript and (conditional) CSS to switch to the 400 pixel version at about 600 pixels screen width. I do this by using a CSS media query and rewriting the meta viewport tag with Javascript.&nbsp;

With this technique, you can make ANY website responsive in about 3 hours, and this includes testing.

I found this quote on Twitter:&nbsp;

> "After 14h straight I think it’s time I call it a day… responsive design is hard"

Do you feel the same? Try this technique! It will surely change your perspective.

PS.&nbsp;If you want to go all fancy, you can add an in-between version for portrait tablets.