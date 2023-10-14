---
title: 'Tarkov Community - I came back but Twitter is no longer here.'
description: 'A website for Tarkov!'
date: 2023-10-14T18:00:00+01:00
image:
---

Better later than never, but also I put this project on a hold while Twitter had it's meltdown and turned into our favourite safe for work wbeiste called X.com...

The original idea revolved around Twitter and the Twitter account [@tarkovcommunity](https://twitter.com/tarkovcommunity) being updated - however the owner dropped that project so it's very much needing to pivot.

My ideas are:

- It's a place to go for anything you need for Tarkov
- It shows live events that are on-going
- It can change seasonally
- (Optional) It utilises Logicals [Tarkov API](https://docs.tarkov-changes.com/#introduction)

To at minimum tidy this up I've removed the map because it doesn't really suit my idea. I hoped to have it a bit more of an interactive map and it doesn't really lend itself to that. I did think something like having regions but that doesn't lend itself to Tarkov's map! I could have done some regions with image manipulation and use some fancy JavaScript animation if it was something we could overlay!

Instead I decided to have a top navigation bar, I did try using Bootstrap's built-in navbar but it didn't make me real happy. I ended up just using buttons that I flexed.

I also hoped to add new theme colours through SASS but this didn't work for some reason, need to do more investigation into that.

I did build out a JavaScript object that stores static data about Tarkov maps. I'd love to build this solution out in somethign like React/Vite with a Firebase/PouchDB (I also saw WatermelonDB) to store the data. I think if I did this I could store the Tarkov API data without making calls each time! Maybe have a "last synced" entry and if it's more than 12 hours old it'll pull the data to save pulling the data each time.

I also want to implement more solutions such as the halloween/Christmas/seasonal events that can be easily spooled up with flags. Maybe also a "X days since wipe".

Lots of ideas, but that means I'd need to come back to develop this and life may get in the way again!

Till next time 👋
