---
layout: post
title: "Shortest Paths in Europa Universalis IV (bachelor's project)"
---

![eu4 gui](https://raw.githubusercontent.com/besplago/besplago.github.io/main/_images/eu4_1.png)
*Europa Universalis IV's gameplay and user interface. The green magnification indicates a player unit. The red magnification indicates the date and game speed.*

For my bachelor's project in computer science at the University of Copenhagen, I chose to investigate the concept of shortest paths in the grand strategy game Europa Universalis IV (EU4). The goal of this project was to explore the different methods of finding the shortest paths between provinces in the game and to evaluate the effectiveness of these methods in enhancing the currently static pathfinding system in the game.

![algorithm](https://raw.githubusercontent.com/besplago/besplago.github.io/main/_images/eu4_2.png)
*Graphical visualization of an algorithm's execution on the EU4 map. Yellow pentagon represents the player, green diamond represents the end province, white triangles represent provinces on the discovered path between the start and end provinces, red stars represent enemies. Algorithm used: bidirectional A\*, enemy frequency: 30%*

The game features a static pathfinding system that calculates the shortest path between provinces based on the distance between them. The system does not take into account factors such as terrain, fortresses, and hostile armies, which can affect the time it takes to travel between provinces. The goal of this project was to develop a dynamic pathfinding system that takes these factors into account and provides more accurate and realistic paths for the player to follow.

The project was implemented using Python.

The full [report](https://github.com/besplago/besplago.github.io/blob/main/_files/eu4_report.pdf) (in Danish).

---
{: data-content="Abina, Saxena, Throw up the... uh-huh"}
