# Hi, I'm Sean Duggan 👋
### Unity Developer | Game Programmer | Technical Designer

I am a Game Developer focused on building modular systems, immersive VR/AR experiences, and polished gameplay mechanics. My work spans from high-fidelity HDRP environments to deep-dives into the Unity Input System and physics-based logic.

---

## 🛠️ Technical Skills
| Category | Technologies |
| --- | --- |
| **Engines** | Unity (HDRP, URP, 2D/3D), AR Foundation |
| **Languages** | C#, HLSL (Shaders) |
| **Systems** | New Input System, Cinemachine, Timeline, XR Interaction Toolkit |
| **Tools** | Git, ProBuilder, Filebase, Photoshop |

---

### 🚀 Galaxy Shooter 2D
<details>
<summary>View Project Details</summary>

This project showcases the development of a feature-rich 2D arcade shooter built in Unity, focusing on modular systems and polished gameplay mechanics. I implemented a robust **Spawn Manager** utilizing weighted probability lists to balance game difficulty, alongside a multi-stage **Wave System**. The project highlights advanced AI behaviors, including enemies with "smart" logic—such as detecting player position to fire backward, dodging incoming fire, and aggressively ramming the player. I also focused heavily on "Game Feel" by integrating post-processing effects, camera shake, and progressive damage VFX to create an immersive player experience.

[Medium Articles](https://medium.com/@sean.duggan/list/space-shooter-78bc4d7acf16)

* **Modular Power-up System:** Engineered a flexible system for diverse pickups, including homing missiles, multi-hit shields, and "negative" power-ups, using C# coroutines and attraction logic.
* **Advanced Enemy AI:** Scripted multiple enemy variants with distinct movement patterns (caroming, aggressive ramming) and tactical behaviors like resource denial (shooting player power-ups).
* **Dynamic UI & Systems:** Developed a comprehensive UI for ammo management, health tracking, and wave notifications, integrated with a scene management system for seamless game loops.
* **Boss Encounter Logic:** Designed and implemented a multi-phase boss fight featuring unique attack patterns, including proximity mines and homing missile salvos.
* **Performance & Polish:** Optimized the game for WebGL deployment and utilized Unity’s Post-Processing Stack (Bloom, Color Grading) to achieve a high-fidelity arcade aesthetic.

</details>

### 🏢 Office Scene: Level Design & Lighting
<details>
<summary>View Project Details</summary>

This project focuses on environmental storytelling and high-fidelity interior rendering within Unity. I transformed a conceptual space into a detailed professional office using **Filebase assets**, focusing on realistic set dressing and spatial flow. The project highlights my ability to work within the **High Definition Render Pipeline (HDRP)** to achieve AAA-quality visuals through sophisticated lighting and material setups. I also utilized **ProBuilder** for greyboxing and creating custom architectural meshes, ensuring the environment was both functional for gameplay and visually compelling.

[Medium Articles](https://medium.com/@sean.duggan/list/office-scene-4594b3187d56)

* **HDRP Lighting & Volumetrics:** Implemented advanced lighting solutions, including volumetric light fog, physically-based light intensities, and baked reflection probes to create a realistic indoor atmosphere.
* **Custom Modeling with ProBuilder:** Developed bespoke architectural elements and light-volume meshes using ProBuilder to supplement standard assets and refine the scene's geometry.
* **Environmental Storytelling:** Expertly placed props and organized "clutter" to create a realistic, lived-in office aesthetic, focusing on composition and player perspective.
* **Material & Texture Optimization:** Managed complex HDRP materials, including emissive textures for monitors and glass shaders for office partitions, to enhance surface realism.
* **Post-Processing Stack:** Fine-tuned global volume overrides such as Color Grading, Bloom, and Depth of Field to give the final render a polished, cinematic look.

</details>

### 🥽 VR Escape Room: Interactive Immersion
<details>
<summary>View Project Details</summary>

This project explores the design and implementation of a fully interactive Virtual Reality escape room built with Unity and the **XR Interaction Toolkit**. The focus was on creating tactile, intuitive interactions that bridge the gap between player intent and virtual physics. I developed a series of interconnected puzzles using **XR Socket Interactors** for key-and-lock mechanics, alongside custom **XRSnapInteractors** for complex object manipulation. To ensure player flow and prevent frustration, I engineered a multi-tiered **Hint System**—including in-universe "Gaze-activated" journals and a dynamic UI hint list—that gradually guides the player based on their progress and perspective.

[Medium Articles](https://medium.com/@sean.duggan/list/escape-room-37d6aac687ba)

* **XR Interaction Toolkit Mastery:** Leveraged the XR Interaction Toolkit to handle advanced locomotion (Teleport/Continuous) and complex object interactions, including custom hand-presence and haptic feedback.
* **Socket & Multi-Layer Logic:** Implemented XR Sockets with dedicated Interaction Layers to ensure only specific quest items (like keys or puzzle pieces) could trigger animations and state changes.
* **Physics-Based Control Systems:** Designed interactive "In-Game" controls such as functional levers, joysticks, and dials for mechanical puzzles, using dynamic events to map physical movement to game logic.
* **Context-Aware Hint System:** Scripted a "Gaze-to-Reveal" hint system and a persistent UI hint log that uses logic to provide progressively detailed clues, mimicking classic adventure game mechanics.
* **Environmental Animation & VFX:** Integrated Unity’s Animator with XR events to trigger environmental responses—such as opening doors or revealing hidden compartments—upon successful puzzle completion.

</details>

### 📱 Mobile AR: Dynamic Object Placement & Visualization
<details>
<summary>View Project Details</summary>

This project focuses on cross-platform mobile Augmented Reality (AR) development using **AR Foundation** and **ARCore/ARKit**. I developed a robust application that allows users to detect real-world planes and interactively place, move, scale, and rotate high-fidelity 3D assets (such as vehicles and turrets) within their physical environment. A key highlight of this project is the implementation of two distinct visualization scales: a **Desktop Mode** for tabletop examination of miniaturized models and a **Driveway Mode** for 1:1 life-sized visualization, allowing users to physically walk around and inspect salient features via informative proximity-based labels.

[Medium Articles](https://medium.com/@sean.duggan/list/unity-ar-686b0dceb815)

* **Advanced XR Interaction:** Integrated the **XR Interaction Toolkit** to support complex mobile gestures including tap-to-place (Raycasting), pinch-to-zoom (Scaling), and swipe-to-rotate.
* **Smart Placement Logic:** Engineered a custom Manager using C# Hashtables to enforce placement constraints, ensuring only one instance of a specific object exists in the scene at a time.
* **Contextual UI System:** Designed a responsive Unity UI with automatic layout groups that dynamically updates available actions (Examine, Remove, Reset) based on the current object selection.
* **Spatial Environmental Awareness:** Leveraged AR Plane Detection and AR Background Renderer features to ensure virtual objects grounded realistically on physical surfaces.
* **State Management:** Implemented a multi-mode system that transitions between "Placement" and "Examine" states, utilizing custom logic to handle location drift and scene resets for a smoother user experience.

</details>

### 🛸 Spaceship Cinematics: Timeline & Cinemachine
<details>
<summary>View Project Details</summary>

This project demonstrates the creation of a high-fidelity cinematic experience centered around a space transport vessel in the **High Definition Render Pipeline (HDRP)**. I utilized **Unity Timeline** to orchestrate complex sequences involving multiple tracks—including animation, audio, and VFX control—to bring the ship to life with custom thruster particles and environmental dust effects. A key technical focus was the integration of **Cinemachine** to handle dynamic camera transitions between external chase views and a detailed cockpit interior, alongside a "sleep mode" logic that automatically triggers a cinematic flyby sequence if no player input is detected.

[Medium Articles](https://medium.com/@sean.duggan/list/spaceship-project-eeea4e6f7ed1)

* **Timeline Orchestration:** Managed multi-track sequences using Animation, Activation, and Control tracks to synchronize spaceship movement with particle effects and layered ambient audio.
* **Cinemachine State Switching:** Implemented a Virtual Camera system that allows for seamless blending between gameplay-ready views and scripted cinematic shots.
* **HDRP Visual Polish:** Leveraged HDRP’s advanced rendering capabilities, including custom skyboxes and volumetric lighting, to achieve a professional sci-fi aesthetic.
* **VFX & Particle Integration:** Developed custom thruster effects using the Unity Particle Pack, upgrading textures for HDRP compatibility and utilizing Control tracks for precise timing during flight sequences.
* **Idle-Triggered Cinematics:** Scripted a logic-driven system that monitors user inactivity to transition the game into a "Cinematic Mode," showcasing the environment through curated camera paths.

</details>

### 🎯 Shooting Gallery: Logic & Interaction Lab
<details>
<summary>View Project Details</summary>

This project is a comprehensive study of modular game systems and interactive mechanics within a 3D shooting gallery environment. I utilized this build to experiment with diverse game logic patterns, specifically focusing on how to decouple object behavior from player input. By implementing **C# Interfaces**, I created a highly scalable interaction system where targets, environmental hazards, and UI elements respond to damage or triggers through unique, scriptable behaviors. The project also highlights advanced physics implementation, including projectile ballistics and destructible object logic.

[Medium Articles](https://medium.com/@sean.duggan/list/shooting-gallery-d746a1d9ec93)

* **Interface-Driven Architecture:** Leveraged `IDamageable` interfaces to allow a single shooting script to interact with a variety of targets—such as pop-up bipedal figures, rotating plates, and explosive canisters—without tight coupling.
* **Dual Shooting Systems:** Developed and compared both **Raycast** (instant hit) and **RigidBody Projectile** (physics-based) weapon systems to handle different gameplay requirements and visual feedback.
* **Dynamic Target Systems:** Scripted complex target behaviors, including path-following movement, randomized "peek" timers, and physics-based hit reactions using Unity’s animation and physics engines.
* **Centralized Game Manager:** Engineered a singleton-based Game Manager to track player performance, manage high scores via Persistent Data, and control the global game state (Start/Active/Game Over).
* **Audio & Visual Feedback Loops:** Integrated a tiered feedback system using Audio Spatialization and particle effects to provide immediate, satisfying confirmation for successful hits and environmental interactions.

</details>

### ⚽ Physics Lab: Ball Game
<details>
<summary>View Project Details</summary>

This project is a deep dive into the Unity Physics engine, focusing on creating a responsive, momentum-based gameplay experience. I explored the relationship between **Rigidbodies**, **Colliders**, and **Physic Materials** to fine-tune object behavior, ensuring smooth movement across various surfaces. The project showcases my ability to manipulate physical forces such as torque, drag, and velocity to solve environmental puzzles. Additionally, I implemented custom physics-based obstacles, including pendulums and conveyor belts, to test the limits of Unity’s constraint systems and collision detection.

[Medium Articles](https://medium.com/@sean.duggan/list/ball-game-d0a1bf5a3384)

* **Advanced Rigidbody Control:** Mastered the use of `AddForce`, `AddTorque`, and velocity manipulation within the `FixedUpdate` cycle to create a precision-controlled player character.
* **Physic Materials & Friction:** Developed a variety of surface types (ice, high-friction, bouncy) using custom Physic Materials to dynamically alter the player's momentum and handling.
* **Environmental Mechanics:** Built interactive physics objects such as gravity lifts, rotating bridges, and weight-sensitive pressure plates using Joint components and Trigger logic.
* **Collision Matrix Optimization:** Leveraged Unity’s Layer Collision Matrix to efficiently manage interactions between complex geometry and moving actors, reducing overhead and preventing clipping.
* **Dynamic Camera Tracking:** Integrated a custom camera follow script that accounts for high-velocity physical movement, preventing jitter and maintaining player orientation during rapid transitions.

</details>

### 🎮 Game Logic & Interaction 2 (GL&I 2)
<details>
<summary>View Project Details</summary>

This project serves as an advanced exploration of player interaction and world mechanics within a 3D environment. I focused on building modular, reusable systems for environmental puzzles and inventory management. A major technical highlight was the implementation of the **New Input System**, where I utilized **Action Maps** to seamlessly swap between character movement and UI-based interactions, such as multi-level elevator controls. I also developed an interface-driven interaction system to handle diverse world objects—from weight-sensitive pressure plates and keycard-locked doors to lootable treasure chests that utilize UnityEvents for decoupled logic.

[Medium Articles](https://medium.com/@sean.duggan/list/gli-2-eb1f3ae03575)

* **Advanced Input Handling:** Implemented the New Input System with Action Map switching to manage context-sensitive controls for gameplay, UI navigation, and interactive objects.
* **Modular Interaction System:** Built a robust system using C# Interfaces to handle various player-to-world interactions, including pickups, switches, and complex environmental triggers.
* **Inventory & Loot Logic:** Developed a functional inventory system to track keycards and loot, integrated with a sci-fi container system that dispenses items via physical pivot-point animations.
* **Dynamic Environment Mechanics:** Engineered multi-state puzzle elements including pressure plates with weight detection, power cell sockets, and elevators with floor-selection UI.
* **Visual State Feedback:** Utilized Material Instances and Emissive textures to provide immediate visual feedback for object states, such as changing light colors when a door is unlocked or a terminal is activated.

</details>

### 🎓 Capoeira Quiz Game
<details>
<summary>View Project Details</summary>

This project demonstrates the application of game design principles to educational content, specifically focused on the history and movements of Capoeira. I developed a structured quiz system that emphasizes user experience through clear UI feedback and logical progression. The project involved managing large datasets of questions and answers, implementing a scoring system that tracks player progress, and designing a responsive interface that adapts to different screen sizes. This project highlights my ability to combine niche subject matter with technical implementation to create an engaging, informative experience.

[Medium Articles](https://medium.com/@sean.duggan/list/capoeira-quiz-game-3bccb6336171)

* **Data-Driven Quiz Logic:** Scripted a flexible system to load and display quiz questions, managing correct/incorrect state transitions and randomized answer placement.
* **Responsive UI Design:** Leveraged Unity’s UI Toolkit and Anchor system to create a clean, mobile-friendly interface with consistent scaling across various resolutions.
* **Feedback & Reward Systems:** Implemented immediate visual and audio feedback for user selections, coupled with a final results screen that calculates performance based on accuracy and speed.
* **Progressive State Management:** Built a state machine to handle the flow from the main menu through active gameplay rounds to the final score tally.
* **Educational Integration:** Focused on "Edutainment" by integrating specific cultural and historical data into a gamified loop, ensuring information retention through repetitive engagement.

</details>

### 🗡️ Dungeon Escape: 2.5D Platformer
<details>
<summary>View Project Details</summary>
Dungeon Escape is a 2.5D side-scrolling platformer that focuses on classic action-adventure mechanics and AI behavior. I implemented a robust player controller featuring double-jumping and combat mechanics, alongside a variety of enemy types with unique patrol and attack patterns. The project showcases my use of **Tilemaps** for efficient level design and the **Singleton Pattern** for managing game-wide systems like currency and diamond collection. Additionally, I explored the integration of specialized animations and hit-detection logic to create satisfying combat encounters between the player and dungeon-dwelling enemies.

[Medium Articles](https://medium.com/@sean.duggan/list/dungeon-escape-9b27f33be92a)

* **2.5D Character Controller:** Developed a responsive player movement system featuring gravity-based physics, multi-jump capabilities, and a modular animation state machine.
* **Enemy AI & Waypoints:** Scripted varied enemy behaviors (Moss Giant, Spider, Skeleton) using waypoint-based patrolling, proximity detection, and unique combat triggers.
* **Tilemap Level Construction:** Utilized Unity’s Tilemap system to create intricate, layered dungeon environments with collision-ready terrain and decorative background elements.
* **Economic System:** Implemented a diamond collection and shop system, utilizing the Singleton pattern for a centralized Game Manager to track player progress and currency.
* **Combat & Hit Detection:** Engineered a hit-box system for sword swings and projectile attacks, ensuring precise interaction between player attacks and enemy health components.

</details>

### 🕹️ Unity Input System Migration: Generic Action Puzzler
<details>
<summary>View Project Details</summary>
This project focused on the technical refactoring of a legacy "Action Puzzler" by migrating it from the old Unity Input Manager to the modern **Unity Input System**. The goal was to replace hard-coded polling logic with a more flexible, event-driven architecture. I utilized **Action Maps** to cleanly separate gameplay movement from UI interactions and implemented support for multiple input devices (Keyboard, Gamepad). This migration not only improved code maintainability but also allowed for more complex input handling, such as distinguishing between simple taps and sustained holds for puzzle-solving mechanics.

[Medium Articles](https://medium.com/@sean.duggan/list/generic-action-puzzler-fbfd773b2213)

* **Legacy Refactoring:** Successfully decoupled input logic from movement scripts, replacing `Input.GetAxis` calls with an event-driven `PlayerInput` component architecture.
* **Multi-Device Support:** Configured Input Action Assets to provide seamless "Plug-and-Play" support for both Keyboard/Mouse and various Gamepad controllers via the New Input System.
* **Contextual Action Maps:** Engineered a system to dynamically switch between "Player" and "UI" Action Maps, ensuring controls are automatically remapped when menus or puzzles are active.
* **Rebinding Ready:** Built the foundation for user-end key rebinding by utilizing the Input System's asynchronous binding overrides and JSON persistence logic.
* **Performance Optimization:** Reduced CPU overhead by moving away from frame-by-frame input polling to a more efficient callback-based notification system (`performed`, `started`, `canceled`).
