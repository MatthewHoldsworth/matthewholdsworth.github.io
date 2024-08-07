# My Portfolio 

### Introduction
I’ve had the opportunity to work on a number of incredible projects that I’m pleased to share. Not only do I enjoy showcasing my work, but also sharing details about the creative process behind each project. Feel free to browse through my portfolio.

### Physics Engine C
This is my 4th year project on game engine mechanics such as physics, AI, and automata's. In this project the player can control a goat player object that's object is to collect points and a key to escape a maze, while there is a goose AI that chases the player and points. The game has a time limit of 60 seconds. There are also menus in which the game can be pause and the player can increase or reduce there move speed to change the games difficulty.

Learning Outcomes:
- Experience programming a C++ physics based engine
- Programmed three implementations of AI/state-based behaviours
- Implemented and applied pathfinding algorithms to AI agents

What Could Be Improved:
- Orientation constraints could have been implemented
- Pathfinding could be improved by implementing nav meshes
- More gameplay elements could be added such as better level design/textures
- A proper menu system that appears in game using middleware

[Link to Project](https://github.com/MatthewHoldsworth/PhysicsEngineC)

### Programmatic-Planet-Rendering
This was my dissertation project for 3rd year, the aim of this project was to implement a variety of methods of procedural generation. Then record performance metrics of these methods at many levels of fidelity, and in evaluation compare them against one another.

[Link to Project](https://github.com/MatthewHoldsworth/Programmatic-Planet-Rendering)

### CSC3231-UnityGraphics
This project was an early 3rd year unity project. This was an introduction into game developments aspects such as shaders, scene graphs and particle systems. Its a rough piece of work that I have included as it contains some work I'm proud such as the water shader, camera controls and billboards.

[Link to Project](https://github.com/MatthewHoldsworth/CSC3231-UnityGraphics)

### OpenGLGraphics
4th year C++ project that's focus was on creating a graphics rendering system. This included implementing features such as multiple lights, scene graphs and bump mapping, among others to create a scene that a scene that contains these features while maintaining a high frame rate. This scene also includes shaders that implement greyscale and blending.

Learning Outcomes:
- Used OpenGL to bind and execute shaders in GLSL
- Implemented a scene with multiple light sources
- Used and applied post processing techniques

What Could Be Improved:
- Lighting model could be improved with shadow mapping
- Reflections of mesh geometry could be added to water
- More geometry could be added to main scene along with the animated skeletal mesh

[Link to Project](https://github.com/MatthewHoldsworth/OpenGLGraphics)

### C Programming Module
This project is entirely my own work. This was to solve a problem regarding polynomial equations. The program can generate polynomials according to some specifications in the readme, it can generate a set of outputs for a range of x values. It can save and load output set and regenerate the polynomial equation used to generate them.

[Link to Project](https://github.com/MatthewHoldsworth/CProgrammingModule)

### 3DTBS (3 Dimensional Turn Based Strategy)
This was a hobby project started in January 2024, part of my motivation behind project was to refamiliarise myself with Unity, as well to mimic to gameplay from games I enjoy. The intent was to have a pathfinding system in a grid, like in Fire Emblem or XCOM, where the player could plot the direction and path of the controlled character or if that path was invalid have the game generate the quickest path. The idea being if there was a hazard the player could navigate their character around it or could simply have the game generate the quickest path if number of moves was important. For this I created a grid like map in which each node (tile) is linked to another which represents adjacency. A character with a number of movement points was created and a control scheme implemented to select the character or tiles in the grid. From here a breadth first search algorithm was created, which would get all possible moves of the character and their distance from the characters origin, theses tiles would be highlighted for the user. Then the user hover a tile it is added to a path list, if the tile is invalid due to it already being in the list, the list being greater than the number of moves or the tile being out of range, the game generates its own path of tiles to the destination if possible. When right clicking the character executes its move path, following the tiles within this path.

Contained within this project is some use of Unity features that were new to me such as the Input system, which is used to control the character, an event based system to notify other scripts via components and the UI toolkit, which provides  information about the character selected and the tiles such as names and adjacency.

[Link to Project](https://github.com/MatthewHoldsworth/3DTBS)

### CV
#### Summary
Graduate of Newcastle Universities Game Engineering Masters course, hired to Nomad Games as Unreal Engine programmer for 1+years. With a passion for all kinds of video games and am looking to further expand my skills and understanding of game development in a professional environment.
#### Work Experience
Nomad Games – Programmer – April 2023 – August 2024
- I was brought on to Nomad Games, while completing my dissertation, to build up their Unreal Engine capacity, this included working on several Unreal projects at the studio and completing training in advanced C++ and Unreal systems such as GAS. 
- I was hired along with 2 other Programmers, and together with Artists, Designers, and members of Marketing we collaborated in a team to work on ‘Board Game Cafe’. This included participating in meetings to discuss features and production targets, as well as self-managing and cooperating on tasks with the other programmers.
- Our efforts were well received by management who who were satisfied with both the quality of our work and the conduct in which we self-managed ourselves and cooperated with other departments at Nomad.
- Builds of the product were made and sent out at various stages of development to publishers and received positive feedback. These demo builds were made within deadlines and contained features specific to informing publishers of the game.
- Having been more experienced in Unity than Unreal I faced many challenges when being brought on. Due to the size of the team I was expected to work on almost every aspect of the game. I had to quickly learn how to develop unreal Behaviour Trees, UI Widgets and Blueprints. I coped with this by practising and learning about these systems outside of work, and over many iterations my work on these systems within the project improved and was brought up to a higher standard.
- From my time at Nomad I have used wide range of Unreal systems such as Unreal Insights, Behaviour Trees, Materials, Environmental Query System, Gameplay Ability System, UI, Animations and its Blueprints.

#### Education
Newcastle University
Master of Computing with First Class Honours in Computer Science (Game Engineering)
Postgraduate:
- I built up a good understanding of C++ and how to develop in an object-oriented paradigm. I gained a solid grasp of memory management and how to write memory safe C++ code. In addition, I learned about other C++ features such as: lambdas, templates, and dynamic memory allocation.
- Using C++ and OpenGL, I created a graphical scene utilising advanced techniques such as multi real time lightning, skeletal animation, and post processing techniques like blurring and grey scaling. I also gained experience writing shaders in GLSL which allowed me to apply my knowledge of the graphics pipeline.
- I used C++ to build upon a game engine framework, adding features such as: collision response/detection, physics, scene hierarchy and AI.
- I was a part of s C++ team project to deliver a multiplayer, cross platform game, within an agile development cycle and taking full advantage of version control and continuous integration.
Undergraduate:
- I learnt about C# and HLSL and how to utilise them when creating a graphical scene in Unity. The scene recorded and displayed performance, running above the 60 frames per second threshold.
- I had the opportunity to explore and implement a wide variety of game development techniques such as: boids, collision response and state management. I also expanded on my knowledge of object-oriented programming and scene hierarchies.
- I collaborated with a group of peers to create a mobile application that simulated online banking. This was accomplished using AWS cloud storage with its SDK. This project involved an investigation into security features, such as credentials, checksums, and RSA encryption.
A-Levels – History(A), Computer Science Advanced (B), Mathematics (C)
10 GCSEs – Grades A* - C including English and Maths

#### Related Skills
Teamwork: From working with and organising projects at University to working within a professional team to build a game from the ground up at Nomad, I have worked competently and cooperatively within a teams, assigned and delegated tasks based on my own and others strengths, and participated in guiding the development of projects.

Organisation: I have been able to manage my own time well as well as others by taking part in or leading team projects, societies, and clubs. This was especially so at Nomad where I and the other programmers organised ourselves and self-assigned tasks based on our prior experiences or preference.

Diligence: I have met or exceeded the boundaries set throughout university and at Nomad through persistent practice at home as apart of hobby projects and independent exploration of solutions and techniques online for the purpose of understanding them. 

Programming Languages: C++, C#, C, GLSL, HLSL, Java and Python
- I was awarded the Bebras gold certificate for completing the organisation's elite challengers that aim to test problem solving skills in 16- to 18-year-olds. This was done outside of my 6th forms curriculum as a way for me to improve my problem-solving skills and sharpen them in a way I can apply when working on computer science projects.
- I have a love of both video and tabletop games, I have collections of board games, video games and trading cards. I have pursued this interest within clubs such as the tabletop and board game society. I also managed a tabletop club at my secondary school for 2 years.
- I am passionate about the techniques of making video games and fascinated with their implementation. I regularly spend my spare time creating projects to try out new ideas I came up with throughout the day or pick up and learn the basics of a new game engine or programming language. I also explore game concepts through online tutorials and videos.

References are available upon request

### Links
[LinkedIn](https://www.linkedin.com/in/matthew-holdsworth-449535264/)

[GitHub](https://github.com/MatthewHoldsworth)
