# Unity Game Developer

#### Technical Skills: Unity, C#, C++, URP, Blender, Gimp, Reaper

<br>

## Projects


### LADA (Las Aventuras de Arturin)
I joined this project to further its development, primarily serving as a gameplay programmer. 
Here are some of the contributions I made:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Wlupngs4lzk?si=KlkIpI37rfFjhvqC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
#### Map Scene Navigation System
I had to create from scratch a system that allows the player to move between different scenes by interacting with a map. The next scene is preloaded while the animation of the character running through the map is active, and it is activated once the animation finishes. The system also provides options to set the sprite and sound effects for the traveler animation, allowing for customization and future flexibility.
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/sAwMjHPcqTo?si=qLePxH1pQp4msxHJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
#### Inventory System
An inventory system with item combinations and the ability to drag items outside of the inventory to an "active item zone". This functionality also enables interaction with objects in the scene.
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/BCZ6TsmlzEY?si=d1yqyGT-totU0XFd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
#### Interaction System
A system that enables players to interact with specific objects in the scene, triggering conversations or various events as needed. This design offers flexibility in how interactions and events are managed.
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/V5X6_3oU_JM?si=gt5DoXTkYw8Y2QC8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
#### Movement System
I had to rework the previously implemented third-person controller, as it was not functioning properly. Additionally, I added several functionalities, including jumping, switching between running and walking and dynamic sound effects based on the ground type, among other improvements.


<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/T0yJ5YOxNbA?si=gyvSiZRQr8w9s1YM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
### [Procedural Planet Generation](https://github.com/LucasNahuelGarcia/Unity-Generators)
A procedural planet generator that uses Perlin noise and marching cubes to generate meshes.
Using the marching cubes algorithm, it creates a spherical object that resembles a planet. The surface is modified by adjusting the value function for each point.
The color was then customized using a shader based on the face direction.
The atmosphere was generated using a sphere with a custom shader that emulates light refraction.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wJx2vfQpU4o?si=iIbbIqX5XkDb5rol" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
### [Procedural Land Generation](https://github.com/LucasNahuelGarcia/Unity-Generators)
A chunk-based terrain system with GPU-instanced grass.
It aims to generate an infinitely explorable world using various layers of Perlin noise as a base to create large and small land features. The system generates the terrain data using a compute shader and then creates a mesh of a configurable resolution that mimics that noise.
This system works with multiple terrain generators that function in conjunction to move with the player, creating a seamless experience.
The grass is based on the billboarding technique and is GPU-instanced on the terrain.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/alfp23qak38?si=E63Qh_AHR5ZgrINK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
### [Untouchable Juan](https://github.com/LucasNahuelGarcia/UntouchableJuan)
A simple fighting game created to test inverse kinematic functionality in Unity.
The game focuses on simulating realistic limb movements in response to player input.

When the player clicks on the scene, the game casts a ray from the camera, determining the target point in the 3D space. The corresponding arm then moves using inverse kinematics to attempt a hit. If the arm successfully strikes an enemy, the enemy transitions into a ragdoll state

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ax5wGTbubAw?si=RI39P3xGUqkkLSIm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
### [Procedural Ocean Simulation](https://github.com/LucasNahuelGarcia/URPOceanShaders)
A URP Shader that uses displacement to emulate ocean behaviour using Gerstner-Waves. 


<br><br>

## Work Experience
**Unity 3D Developer @ Youvi Systems (_June 2023 - February 2024_)**
- Managed 3 different projects in VR for mobile.
- Reduced APK size to 35% by optimizing texture compression and reworking unoptimized meshes in Blender.
- Reworked a 12GB  abandoned demo project, following SOLID principles and implementing better design patterns. Allowing for future scalability and reducing the time needed to implement changes and add features.
- Modeled more than 25 assets in Blender, for use in multiple scenes.
- Designed and implemented more than 20 UI systems for both VR and non-VR settings.

**Unity 3D Freelance Developer @ Fiverr (_May 2021 - Present_)**
- Developed a question-based game with an online scoreboard using Google FireBase.
- Created a Cardboard VR Demo.
- Designed and implemented movement mechanics, scene management systems, inventory systems, and more.
- Currently maintaining multiple projects, providing IT solutions such as problem-solving, technical advice, and gameplay system development for multiple clients.

**Programming Intern @ Servicios Públicos Río Gallegos (_July 2018 - December 2018_)**
- Designed and implemented a system to ease electrical meter data readings and storage.
- Constructed a backend with securely stored passwords, using the latest best practices for password handling.
- Scraped thousands of entries from an outdated and poorly structured Cobol database into a new MongoDB one, using a Node.js script.


## Education
- Licenciatura en Ciencias de la Computación | Universidad Nacional del Sur (_Present_)
- Computer Technician	| Escuela Industrial “José Menéndez” (_December 2018_)
