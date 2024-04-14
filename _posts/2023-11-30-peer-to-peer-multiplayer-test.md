---
layout: post
title: "Godot Multiplayer Test"
---

I have an idea for a multiplayer game that I wanted to make in Godot, yet I had no experience doing
any networking. Therefore, I decided to make a simple peer-to-peer multiplayer test to get a feel
for how it works.

![Peer-To-Peer Multiplayer Test](/assets/images/peer-to-peer-multiplayer-test.png)
*Left window is the host, right window is a peer.*

I played around with both peer-to-peer and server-client multiplayer, though I later found out that
a server-client model is more suitable for my game idea, as figuring out how to prevent cheating in
a peer-to-peer model is quite difficult.

![Peer-To-Peer Multiplayer Test](/assets/images/peer-to-peer-multiplayer-test-2.png)
*Both players attacking a monster and it being synchronized.*

A core idea behind the game is that the combat and movement is based on MMORPGs, so I also
implemented a lightweight version of that in this test.

---
{: data-content="Project W(iP)"}
