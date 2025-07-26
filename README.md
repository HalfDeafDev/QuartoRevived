# Quick Update

While the project has gone "stale" it is definitely not over. The definite struggle with this project is getting a good front-end that works well on "all" platforms.

My work on here will continue as the mood strikes and a better front-end design emerges. In the mean time, I have other projects that I have been working on.

# Quarto Revived

[The first report](./ProgressReports/0/report.md) has been released! I discuss some of work and discoveries found in the pursuit of being friendly to play on all platforms. I also briefly show how building live static mock ups in HTML, CSS, and minimal Javascript can help you focus on on layout and themeing, as well as enabling easier customization features. Please give it a glance!

## What is it?

A rebuild of [an older project](https://github.com/CTheCheese93/Quarto) that decouples the game logic and will include online multiplayer with a focus on a good mobile experience.

## Why not update the old project?

Multiple reasons, some of which include:

1. Wanting to try out VueJS instead of React
1. Decoupling the game logic from the client leaves a non-mobile friendly front end that needs entirely re-done anyways
1. The former was an exercise in translating a board game, this is an exercise in offering an experience

## Technologies Used

This is not a comprehensive list but is up to date as of 2025/01/05 (YYYY/MM/DD).

| Tech | Use |
|-|-|
|Python|Game Engine|
|SocketIO|Communication between Game Engine and Web Server, as well as managing Game Rooms|
|VueJS| Front-End

## Milestones

- [x] Rebuild the game logic in Python
- [ ] Create a front-end
    - [ ] Mobile Friendly
    - [ ] Local Multiplayer
    - [ ] User Registration
- [ ] Public Game Rooms
    - [ ] Chat
    - [ ] Spectators
- [ ] User Preferences
    - [ ] Primary/Secondary Colors
    - [ ] Primary/Secondary Shapes
- [ ] Private Game Rooms
- [ ] Themes
