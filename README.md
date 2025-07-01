
# 💻​Projects Portfolio

This repository contains a curated selection of personal and academic projects I have worked on, listed from most recent to oldest.  
Each project includes a description, purpose, technologies used, media links, and relevant documentation when available.  
Projects span different domains such as software development, game design, AI, and creative prototyping.

---
>.
>
> ⬇️ Below you'll find detailed overviews of each project I've worked on 📁 
>
> .
---



## 🎮​ Pomegranade: Limbo 👨‍💻​

<p align="center">
  <img src="https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Images/copertina.png" 
  alt="Representative Image" width="350"/>
</p>

### 🎯 Purpose  
The goal of this project was to design and develop a multiplayer online game in a team of three people, as the main assignment for the **Online Game Design (OGD)** course.

The course is part of the Master’s Degree in **Computer Science** at the **University of Milan**, and offers a specialized path in **video game design and development**, active since 2014 and unique in Italy. It is known for its collaboration with the **Politecnico di Milano** and strong ties with the game industry.

**OGD**, taught entirely in English, focuses on the **design and technical development of online multiplayer games**, combining disciplines such as game design, programming, computer graphics, AI, UX, and storytelling. It emphasizes **team-based, project-oriented learning**, where students conceive, prototype, and present a complete multiplayer game, culminating in participation in the **New Game Designer** industry showcase.

### 🛠️ Technologies Used  
- Language: `C#`  
- Game Engine: `Unity`  
- Tools & Platforms:  
  - `FMOD` (for dynamic audio design)  
  - `GitHub` (used for version control and team collaboration, including issue tracking and project planning)

### 🎫 Project Description  
**Pomegranade: Limbo** is a cooperative online party game for 2–4 players set in a mystical forest. The core gameplay is structured around **two alternating phases**:

- **Activity Phase (Daylight)**: Players gather resources by engaging in short, cooperative activities directly in the game world—such as chopping wood, harvesting magical pomegranates, and repairing defensive structures. These tasks require coordination, as some actions benefit from being performed simultaneously by multiple players.

- **Combat Phase (Night)**: As darkness falls, waves of shadowy creatures attack the central bonfire. Players must defend it using **pomegranate-based weapons** crafted from the gathered resources. Shooting mechanics are seamlessly integrated with the environment—players aim, charge, and throw projectiles in real-time, with each shot contributing to the team’s survival.

The game also features a **dynamic day–night cycle**, randomized debuffs, and a communication system based on customizable **emoticons**, encouraging strategy and emotional expression without relying on voice chat.

For more details on the game design and especially the implementation of the working prototype, see the full Game Design Document (GDD) and the Game Technical Document (GTD) linked below.

### 🔗 Useful Links
- 🎞️ [Trailer Video](https://www.youtube.com/watch?v=iTNlmDLAY84)
- 🎞️ [Gameplay Video](https://www.youtube.com/watch?v=KJZ43R5dVLI)
- 📄 [GDD](https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Documents/GDD.pdf)
- 📄 [GTD](https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Documents/GTD.pdf)
- 🌐 [OGD Course Page](https://www.unimi.it/it/corsi/insegnamenti-dei-corsi-di-laurea/2025/online-game-design)
- 🌐 [NGD Page](http://ngd.unimi.it/)

---

## 🎮​ Blindrun 👨‍💻​

<p align="center">
  <img src="https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Images/BlindRun-Logo.png" 
  alt="Representative Image" width="350"/>
</p>

### 🎯 Purpose  
This project is currently under development and was started as the main assignment for the **Sound in Interaction** course.

The course is part of the Master’s Degree in **Computer Science** at the **University of Milan**, and focuses on the design and application of **interactive sound techniques** in digital experiences.  
Topics include signal-based and physical-model sound synthesis, spatial audio (e.g., reverberation, binaural rendering), perceptual and cognitive aspects of audio, and toolchains such as **Pure Data**, **FMOD**, and audio pipelines in **Unity** and other engines.

### 🛠️ Technologies Used  
- Language: `C#`  
- Game Engine: `Unity`  
- Tools & Platforms:  
  - `FMOD Studio` (for real-time spatialized audio via 3D events)  
  - `Unity XR Toolkit`, `OpenXR`  
  - `Meta Quest 2` headset (standalone mode)  
  - `GitHub` (for solo development and version tracking)

### 🎫 Project Description  
**Blindrun** is an experimental VR game inspired by the classic game of blind man's bluff (*mosca cieca*), where the player must rely entirely on **sound** and **touch** to navigate and win.

Set in an indoor environment (currently a futuristic sci-fi factory), the player is **completely blind**—no visuals are provided beyond the immediate outline of their **hands**. These hands are used to explore the world by physically touching surfaces and objects.  
When an object is touched, a custom **shader effect** reveals only the exact contact area in partial transparency, simulating the sense of **tactile perception** in an otherwise invisible world.

The objective is to **locate and tag all NPCs** in the environment. NPCs generate distinct, spatialized sounds as they move, speak, or interact with the environment. Each NPC has a different behavior: some hide, some flee, and others move erratically. The player must listen carefully, **interpret spatial audio cues**, and physically move toward the sound source to touch and “eliminate” the NPC.

Movement is fully embodied: players must **simulate running** by moving their VR controllers up and down like real arms. Navigating effectively requires combining proprioception, haptic feedback through hand contact, and a **precise awareness of 3D sound positioning**.

The game is built around the use of **spatialized audio** as the primary gameplay mechanic. FMOD handles all sound logic, with plans to integrate **Resonance Audio** or **Meta’s spatial audio system** for realistic 3D sound propagation and occlusion effects.

The prototype currently features a fixed map and basic enemy AI, with plans for future procedural level generation, multiple NPC archetypes, and progressively complex sound environments.

### 🔗 Useful Links
- 🌐 [Sound In Interaction Course Page](https://www.unimi.it/it/corsi/insegnamenti-dei-corsi-di-laurea/2025/sound-interaction)

---

## 🎮​ MegaMan Battle Network – Full Synchro 👨‍💻

<p align="center">
  <img src="https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Images/MMBN_TitleScreen_Showcase.png" 
  alt="Representative Image" width="350"/>
</p>

### 🎯 Purpose  
The goal of this project was to design and develop a virtual reality experience individually, as the main assignment for the **Virtual Reality** course.

The course is part of the Master’s Degree in **Computer Science** at the **University of Milan**, and focuses on the exploration and application of **VR and AR technologies** using modern tools and development environments.  
Students are required to conceive and implement an interactive prototype that applies core XR techniques to a meaningful, functional, and technically sound project.

### 🛠️ Technologies Used  
- Language: `C#`  
- Game Engine: `Unity`  
- Tools & Platforms:  
  - `XR Interaction Toolkit`  
  - `OpenXR`  
  - `Meta Quest 2 and Meta Quest 3` headsets
  - `GitHub` (for version control and development tracking)

### 🎫 Project Description  
**MegaMan Battle Network – Full Synchro** is a first-person VR reinterpretation of the classic MegaMan Battle Network battle system, developed as a solo project.  
The player takes the role of MegaMan himself, standing on a 3x3 grid of blue tiles, while enemies (virus types) spawn on a symmetrical red grid in front. Combat is fast-paced and arcade-style, blending the strategic layout of the original series with immersive aiming and shooting mechanics in VR.

Combat is handled using the **Mega Buster**, which is physically integrated into the player’s right arm in-game. With the left arm, players can reveal enemies' names and health by bringing the hand near the headset and pressing a specific input—mimicking an in-universe scanning gesture.

The game features:
- **Procedural enemy waves**, with three enemy types, each having six progressively harder variants.
- **Roguelite structure**: when defeated, the player restarts from scratch.
- **Reward system** after each wave group: players may receive **health refills** or temporary **power-ups**.
- A focus on **personal high-score chasing** and endurance-based progression.

The project emphasizes tight mechanic integration, immersive VR interaction, and procedural variability—paying tribute to the original GBA titles while adapting them into a modern, room-scale VR experience.

### 🔗 Useful Links  
- 🎞️ [Demo Video](https://youtu.be/_tBflqcJfOI?si=eE_IQJeeLZzxlxhA)  
- 🌐 [Virtual Reality Course Page](https://www.unimi.it/it/corsi/insegnamenti-dei-corsi-di-laurea/2025/realta-virtuale)  

---

## 🎮​ Drunk Stride 👨‍💻​

<p align="center">
  <img src="https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Images/DrunkStrider.png" 
  alt="Representative Image" width="350"/>
</p>

### 🎯 Purpose  
This project was developed as the assigned exercise for the **Artificial Intelligence for Video Games** course.

The course is part of the Master’s Degree in **Computer Science** at the **University of Milan**, and focuses on the design and implementation of AI systems within interactive virtual environments.  
Topics include AI architecture in game engines, decision-making models, movement and pathfinding, procedural content generation, and introductory techniques in **machine learning** and **genetic algorithms** applied to game development.

### 🛠️ Technologies Used  
- Language: `C#`  
- Game Engine: `Unity`  
- Tools & Platforms:  
  - `GitHub` (for version control)

### 🎫 Project Description  
**Drunk Stride** is a simple AI-based simulation developed in Unity. The objective is to create an autonomous agent that continuously moves across a platform **without ever walking in a straight line**.

The character (a “drunk” NPC) alternates left and right circular motions with **randomly selected radii** and **time intervals**, simulating unsteady, unpredictable movement. At every change, a new radius and rotation direction (left or right) are chosen, ensuring that the agent constantly adapts its path while maintaining a **fixed speed** of 1 m/s.

Key features:
- Circular motion around dynamically updated pivot points  
- Full compliance with movement constraints: the agent never stops or exits the platform regardless of shape or size  
- Modular architecture: components like rotation control, movement logic, and gaze direction are handled by separate scripts  
- Minimalist top-down scene for focused testing

The project was completed individually and aimed to demonstrate understanding of **behavioral scripting**, **randomized decision logic**, and Unity-based agent control systems.
For more information see the **Project Report** linked below.

### 🔗 Useful Links  
- 🎞️ [Demo Video](https://drive.google.com/file/d/1ujFvLfvMSyzhhM5gYqgJi9DMe0GFx1Ux/view?usp=sharing)  
- 📄 [Project Report](https://github.com/LeandroBognanni/Projects-Portfolio/blob/main/Documents/Drunk%20Stride-Project%20Report.pdf)
- 🌐 [AI for Video Games Course Page](https://www.unimi.it/it/corsi/insegnamenti-dei-corsi-di-laurea/2025/artificial-intelligence-video-games)  

---

## 🎮​ Masters of Renaissance – Digital Edition (Java Multiplayer) 👨‍💻​

<p align="center">
  <img src="https://i2.wp.com/www.balenaludens.it/wp-content/uploads/2019/12/maestri-del-rinascimento.jpg?resize=1024%2C600&ssl=1" 
  alt="Representative Image" width="350"/>
</p>

### 🎯 Purpose  
This project was developed as the final team assignment for the **Software Engineering** course during the Bachelor's Degree in **Computer Engineering** at **Politecnico di Milano**.

The course focused on the application of **software engineering principles**, emphasizing structured design, documentation, and best practices in object-oriented development.  
Students were required to start from **UML diagrams** and implement a complete system using the **Model-View-Controller (MVC)** architectural pattern, integrating concepts such as layered architecture, design patterns, testing, and multi-user client-server communication.

### 🛠️ Technologies Used  
- Language: `Java`  
- Architecture: `Model-View-Controller (MVC)`  
- Networking: `Sockets` (low-level TCP communication)  
- UI:  
  - `Swing` (Graphical User Interface)  
  - `Command Line Interface (CLI)`  
- Build Tool: `Maven`  
- Testing: `JUnit 5`  
- Tools:  
  - `GitHub` (version control, project collaboration)

### 🎫 Project Description  
**Masters of Renaissance – Digital Edition** is a full digital multiplayer adaptation of the board game *Masters of Renaissance*.  
The project supports both **GUI** and **CLI** user interfaces and allows players to connect to a shared server instance via socket communication.

Key features include:
- Full rule implementation of the original game
- Multiple concurrent game sessions hosted on the same server
- Advanced functionalities such as:
  - **Disconnection resilience** (players can reconnect mid-game)
  - **Lobby system for parallel matches**
  - **Game parameter editor**: A dedicated GUI tool to modify development card properties, leader card effects, faith track, and more

The game follows a strict **MVC pattern** with a fully decoupled design.  
UML diagrams (both initial and final versions) were produced and maintained, and the codebase is fully documented via **JavaDoc**, alongside a complete **coverage report** of unit tests.

This project was developed in a team of three:

- [Niccolò Bergamaschi](https://github.com/Niccolo-Bergamaschi)  
- [Leandro Bognanni](https://github.com/LeandroBognanni)  
- [Gabriele Brenna](https://github.com/Gabriele-Brenna)

---

## 🤖​ Blades in the Dark Bot – Telegram Assistant for Tabletop RPGs 👨‍💻​

<p align="center">
  <img src="link-to-image.jpg" 
  alt="Representative Image" width="350"/>
</p>

### 🎯 Purpose  
This project was developed as part of a freely chosen elective course during the **Bachelor’s Degree in Computer Engineering** at **Politecnico di Milano**.

The assignment required the creation of an interactive bot in **Python** capable of supporting players in conducting and managing **tabletop role-playing game (TTRPG)** sessions entirely through **Telegram**.  
Our group selected the game *Blades in the Dark* as a reference system, aiming to fully adapt its mechanics into an intuitive chat-based assistant.

### 🛠️ Technologies Used  
- Language: `Python`  
- Libraries & Tools:  
  - `python-telegram-bot` (core conversation handling)  
  - `sqlite3` (persistent data storage)  
  - `Pillow` (for generating visual character/crew sheets as PNGs)  
  - `BeautifulSoup`, `SVG`, `JavaScript` (for dynamic journal and interactive maps)  
  - `GitHub` (collaborative development and version control)

### 🎫 Project Description  
**Blades in the Dark Bot** is a Telegram bot designed to assist players and game masters in managing long-form role-playing campaigns, specifically for *Blades in the Dark*. The bot supports the entire flow of a campaign through Telegram chat, with a focus on accessibility, automation, and narrative structure.

Main features include:
- Creation and management of **campaigns**, **player characters**, and **crews**
- Management of **game clocks**, **resource counters**, and **dice rolls**
- Custom **character sheet generation** in image format, dynamically updated and delivered in-chat
- **Interactive journal system**: stores mission logs and events with dynamic links between entries
- A **narrative map interface** (HTML/JS based) that synchronizes with the journal, showing locations and clickable references to past events
- Multi-user support with **access restrictions**, allowing multiple players to interact asynchronously within the same campaign
- Persistent storage via **SQLite database**, ensuring data is preserved and queryable over long campaigns

The project was developed in a team of three:

- [Niccolò Bergamaschi](https://github.com/Niccolo-Bergamaschi)  
- [Leandro Bognanni](https://github.com/LeandroBognanni)  
- [Gabriele Brenna](https://github.com/Gabriele-Brenna)

### 🔗 Useful Links  
- 📄 [Full Project Report – PDF](https://link-to-pdf)  
- 🌐 [Telegram Bot Page / Demo Site](https://link-if-any)

---

