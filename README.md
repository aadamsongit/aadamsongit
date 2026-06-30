My first professional software engineering role was a year-long contract as an IT Automation Engineer at Takeda Pharmaceuticals through TEKsystems (2023–2024). My primary technical focus was automated testing. I developed and maintained pytest suites for Python applications, participated in testing round robins with my team, and gained practical experience working with production code, structured testing practices, and collaborative software development. The role also introduced me to mocking, unit testing strategies, and professional testing workflows.

When my contract ended in mid-2024, I decided to deepen my frontend knowledge. I revisited React and modern frontend development before beginning work on my first solo application. From February to July 2025, I built and deployed the MVP for Hashle, a Wordle-inspired game.

Hashle was my first end-to-end application that I designed, built, deployed, and maintained myself. Built with React, it relied heavily on local component state and React Hooks, giving me practical experience reasoning about state, rendering behavior, and user interactions. Hashle also achieved excellent Lighthouse scores for performance, accessibility, SEO, and best practices, although I recognize that its relatively simple UI made that easier to accomplish than a larger application.

For the animations, I chose vanilla CSS rather than a JavaScript animation library such as Framer Motion. CSS transitions proved sufficient for the interactions I wanted, although I still encountered and resolved several race-condition bugs while refining the UI.

Hashle exposed me to several frontend debugging challenges. Coordinating React state, CSS transitions, and localStorage persistence led to timing-related bugs that required careful reasoning about state updates and rendering behavior. I also relied on complex JavaScript data structures to manage Wordle state transitions, which reinforced the importance of keeping application logic understandable as complexity grows.

---

## Open Source Contributions:

For about a year, I contributed on and off to Dance Chives, an open source dance event platform that has gradually evolved from a social application toward a more data-driven architecture. I began by pair programming in VSCode with Ben for the frontend of the application. I helped refactor Tailwind for mobile and breakpoints. I also wrote some Neo4J relations, but I would not foreground myself as experienced in Neo4j. 

One of my larger contributions was a holistic refactor of the Minesweeper game (open source by Vinay Gajjar). I applied many of the lessons I had learned while building Hashle, consolidating game state into a single useReducer-based game engine. During the refactor, I identified and fixed a deep-cloning bug, broke apart a monolithic App.tsx component into smaller modules, and extracted reusable logic into pure utility functions. The refactor improved modularity and made the codebase more suitable for testing. Minesweeper is currently ready for testing. 




