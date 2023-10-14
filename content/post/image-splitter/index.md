+++
author = "Alex Jenkinson"
title = "How I made Bigmojis easier to create!"
date = "2023-06-24"
description = "A project so that I can make bigger emojis on Slack for work"
categories = [
    "Projects",
]
tags = [
    "projects",
    "Javascript",
    "programming",
    "web app"
]
image = "kevin-schmid-65es-iLjvVo-unsplash.jpg"
+++

I really love emojis, they really help me accurately portray the meaning behind my messages. We all know async communication can be difficult to convey emotions as we can in person - but I'm neurospicy so I much prefer if people emoji'd me even in real life!

While working I noticed we had some multi-line emojis that I'm coining the term "bigmojis". They're really fun cool, and nice to be able to type a keyword and have them appear such as `biglol` or `elduck` which I both made at work. However to make them involves finding the emoji, slicing it into the amount of squares you want, naming them, uploading this to Slack, creating a Slackbot command and typing out all of command correctly with linebreaks!

It's a lot of hassle, and probably why we don't have as many awesome **bigmojis** out there! So this is where my little hyperfixation comes in - I told a colleague at work I'd make a web app to make it easier for them to join the club!

I knew there **had** to be some library out there, or open source code that you can slice an image into squares and output that. I was right I found one by [RuyiLi](https://github.com/RuyiLi/image-splitter) and it worked! But it worked by pixels and not by "squares" which was my key use case.

I spent my evening after work hyperfocused on making it work and it just didn't so I built a very basic hardcoded 2x2 grid which was a very very bare idea of what I wanted but I was definitely not happy with it.

Then I decided that it was time to get this project done and I refactored the code for my use case! Now I'd consider this attempt at creating this to be a bit like Frankensteins monsters and very patchwork but it's a minimum viable product and it works. You upload an image, select your squares and it'll provide you a ZIP file with the emojis, the code to add to Slackbot and the code to use in messages. I consider that a win!

It was also my first Javascript project ever really outside of practicing and I know I could definitely write it better with more focus on potentially a library for others to use!

You can check it out on my [GitHub](https://github.com/ParagonJenko/slackbot-multiline-emoji-js) or the [website URL](https://alexjenkinson.com/bigmoji)

## Part 2 - The Giffening

While using the tool my Team Manager actually asked if we could do moving images - which I assumed correctly that it was some .gif functionality they were looking for. After a little bit of faffing from my end because I struggled to re-factor this.

## The Conclusion

I don't think there is much more I want to do - other than completely refactor this but I've lost interest in doing that!
