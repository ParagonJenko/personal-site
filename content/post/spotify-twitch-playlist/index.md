---
title: 'The Spotify Twitch Playlist'
description:
date: 2023-07-14T12:00:00+01:00
image:
hidden: false
draft: true
---

# What problem am I fixing?

I'm a long time supporter/friend of [ThatFriendlyGuy](https://www.twitch.tv/moderator/thatfriendlyguy) and on specifics days we run any music, or themed music! Which is a really fun community engagement and also nice to listen to things you actually want to listen to.

But the problem is... we have to manually do this by having the creator or one of the moderators with access to the Stream PC through Remote Desktop to manually setup spotify.

# How am I fixing this?

My first thoughts are:

- The creator has a public Spotify playlist, where viewers go to a website and search for a song which will add to the queue!

Further thoughts are:

- If it's a themed day this adds to an "approval" queue?
- A voting system for what comes up next?

# The Plan

## Step 1 - The API

14/07: Let's setup a Spotify dev account, start a repo and play around with what we can do!

Attempt 1:

- Wireframed + Flexbox'd the HTML+CSS.
- Tried to use PKCE flow authorisation
- Didn't work.

Attempt 2:

- Used the https://developer.spotify.com/documentation/web-api/howtos/web-app-profile web app profile client side application.
- Used the Typescript variant to learn TS.
- Got it working to display the current playlist.
- Couldn't use the search function.

---

# The I Got Bored Of This And Another Solution Was Found So I Stopped

These were the ends of my attempts, I didn't get too far after 14/07's attempts.

I did some tinkering but we found a solution that was baked into a Twitch bot too so there was no immediate need for this and honestly it didn't super excite me enough to continue.
