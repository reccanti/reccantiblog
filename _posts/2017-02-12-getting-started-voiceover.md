---
layout: post
title: Getting Started with VoiceOver for Mac - Basic Navigation
slug: voiceover-basic-nav
category: development
tags: [web, accessibility, screen readers]
header:
  img: /assets/images/SpeakerIcon.png
  caption: "A speaker icon representing MacOS VoiceOver"
---

If you've ever looked into accessibility on the web, you've probably heard that you should test your site with a screen reader. If you're used to scrolling and clicking, this can be a daunting task! Navigating a site with a keyboard is a much different experience, and it's easy to get frustrated if you don't know what to do. This post will cover the basics of navigation with VoiceOver - MacOS's built-in screen reader - hopefully making it a little less scary to get started :)

## Turning VoiceOver On and Off

![Screenshot of the dialog box displayed when opening VoiceOver]({{ site.url }}/assets/images/VoiceOverWelcomeDialog.png)

You can turn VoiceOver on and off using the command: `cmd + f5`. If you're turning VoiceOver on, it will open up a dialog box like the one above. From here, you can keep it on, or to turn it off.

## Basic Navigation with the `VO` Key

![Screenshot of the VoiceOver cursor highlighting the title of the Screen Reader Wikipedia page]({{ site.url }}/assets/images/VoiceOverCursorExample.png)

Basic movement in VoiceOver requires you to use the VoiceOver key (`VO`). For me, this was the `caps lock` key by default. A black outline will appear over the region of the page that is currently being read, with a black box displaying the contents. You can move forward between elements by holding `VO` and pressing the `right arrow key`. Similarly, you can move backward by holding `VO` and pressing the `left arrow key`.

Note: you can tell if your `VO` key is `caps lock` if, when you tap `caps lock`, the green light on the button blinks instead of staying on. Because of this, a single tap will not turn caps lock on. If you want to turn caps lock on or off, double tap the `caps lock` button.

## Interacting with Elements

You can think of interacting with elements like you're drilling down into them to access their individual components. For example, if you were to interact with the browser window, you would get access to individual elements on the page. If you were to interact with a block of text, you would be able to access its individual letters. To start interacting with an element, press `control + option + down`. To stop interacting with that element, press `control + option + up`.

## Selecting Controls and Elements

Sometimes you need to select form elements like radio buttons or interactive elements like links.  To do this, position the VoiceOver cursor over the element and press `control + option + space`.

## Take the Quick Start Tutorial!

![Screenshot of the VoiceOver QuickStart Tutorial welcome screen]({{ site.url }}/assets/images/VoiceOverQuickStartTutorial.png)

If you want to practice any of these things, or if you want to learn more, VoiceOver has a Quick Start Tutorial built-in. To access it, press `VO + h`. This will open the VoiceOver Help menu which has access to online documentation and several references. Scroll down to the Quick Start Tutorial and Select it the way we learned above!

## Recap

In this post, we learned: 

1. `command + f5` opens and closes VoiceOver.
2. `VO + right arrow` moves you to the next section of the document, while `VO + left arrow` moves to the previous. (`VO` is `caps lock` by default)
3. `control + option + down` moves you into an element, while `control + option + up` moves you out of the current element.
4. `VO + h` will open the VoiceOver Help Menu, where you can access the Quick Start Tutorial.

That should give you everything you need to move around a web page on a basic level. What other topics would you be interested in hearing about? 
