---
layout: post
title: "Endless Corridor in Virtual Reality"
---

<style>
    .video-container {
        position: relative;
        padding-bottom: 56.25%; /* 16:9 aspect ratio */
        padding-top: 30px;
        height: 0;
        overflow: hidden;
    }

    .video-container video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

<div class="video-container">
    <video controls style="filter: invert(100%);">
        <source src="https://github.com/besplago/besplago.github.io/blob/main/_videos/endless_corridor_1.mp4?raw=true" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
*Endless Corridor Video Demo*

For the elective course [Virtual Reality](https://kurser.ku.dk/course/ndab20008u/) on my bachelor's degree in computer science, I developed and implemented a locomotion technique called "Endless Corridor". The goal of the project was to create a virtual reality experience that would allow the user to walk through an endless corridor with limited physical space. The user would be able to walk back and forth in the corridor, but the corridor would never end, though the user would never notice this.

<div class="video-container">
    <video controls style="filter: invert(100%);">
        <source src="https://github.com/besplago/besplago.github.io/blob/main/_videos/endless_corridor_2.mp4?raw=true" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
*Endless Corridor technique visualized*

The way we achieved this was by having the player complete some tasks in a virtual corridor that would require them to turn around. When turning around, a rotation gain was applied to the player's view so that they would not notice that when they had completed the task and turned around, they were actually facing the same direction as when they started. This way, the player would never notice that they were walking back and forth in the real world, but would instead feel like they were walking through an endless corridor.

<div class="video-container">
    <video controls style="filter: invert(100%);">
        <source src="https://github.com/besplago/besplago.github.io/blob/main/_videos/endless_corridor_3.mp4?raw=true" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
*On the left, the player is solving a task with Endless Corridor. On the right, the player is solving a task with regular locomotion.*

The project was implemented using the Unity game engine and the Meta Quest 2.

The full [report](https://github.com/besplago/besplago.github.io/blob/main/_files/endless_corridor_report.pdf).
