---
info_box: true
info_box_thumb: /microfolio/content/projects/pro-jank-footy/images/pjf-side-thumb.png
title: 'Pro Jank Footy'
date: '2026'
location: 'Freelance'
description: "An over-the-top arcade comedy-sports game. Score goals to unleash game-changing power-ups, and build a deck of absurd abilities."
developer: 'Powerbomb Games, Tinker Town'
publisher: 'Powerbomb Games, Umbrella Gaming'
release_date: '2026'
status: 'In Development'
platform: 'Steam, PS5, Xbox X|S, Switch 1|2'
links:
  - title: "Steam"
    url: "https://store.steampowered.com/app/3621330/Pro_Jank_Footy/"
role: 'Multiplayer and Technical Designer'
featured: true
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/q-LsnczpGug?si=btHoGLmRZJxVrpKy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


> *With commentary from Aunty Donna's Broden Kelly, and the creative minds of David Ashby and Dario Russo behind cult TV series Danger 5 and Italian Spiderman driving the humor, Pro Jank Footy is jam-packed with comedy, charm and Australianisms.*

- I was primarily brought on as a freelancer mid-way during development of the project to retroactively develop 1v1 online multiplayer gameplay that would work across the Steam, PlayStation, Xbox, and Switch versions of the game.

- This extended to designing and implementing various power cards that change the game mechanics, as well as the technical design for some boss team matches for the Roguelike Season mode

- For the Online, Aside from making it functional and play nicely, my main goals were to:
  1. Not get in the way of regular development
  2. Make it scalable, but also cheap/free to run
  3. Reduce the chance of cert failure on console to mitigate delays
  4. Keep as many of the powers as possible usable in an online game

- I won't go into too much detail here, reach out if you wanted it, but the TL;DR of the stack used was:
  - FishNet: Open-source multiplayer framework
  - Epic Online Systems: For user-auth, and P2P hosting with relays for console compliance

- To reduce complexity I implemented a 5-digit room code system rather than matchmaking, as the target audience of the game is expected to be friends playing together in a call. 

- I also helped out on developing some other minor features, systems, and bugs to help reduce to the dev load on the rest of the team.

- Also fun - I helped out at Pax Aus 2025, and donned the Mr. Footy mascot outfit on the showfloor (it got SWEATY, I tell ya)
<div style="display:flex;gap:12px;align-items:center">
  <img src="/microfolio/content/projects/pro-jank-footy/images/mrfooty.jpg" alt="Pro Jank Footy image 1" style="width:50%;border-radius:4px" />
</div>
