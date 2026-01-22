### 🚀 Galaxy Shooter 2D
This project showcases the development of a feature-rich 2D arcade shooter built in Unity, focusing on modular systems and polished gameplay mechanics. I implemented a robust **Spawn Manager** utilizing weighted probability lists to balance game difficulty, alongside a multi-stage **Wave System**. The project highlights advanced AI behaviors, including enemies with "smart" logic—such as detecting player position to fire backward, dodging incoming fire, and aggressively ramming the player. I also focused heavily on "Game Feel" by integrating post-processing effects, camera shake, and progressive damage VFX to create an immersive player experience.

[Medium Articles](https://medium.com/@sean.duggan/list/space-shooter-78bc4d7acf16)

* **Modular Power-up System:** Engineered a flexible system for diverse pickups, including homing missiles, multi-hit shields, and "negative" power-ups, using C# coroutines and attraction logic.
* **Advanced Enemy AI:** Scripted multiple enemy variants with distinct movement patterns (caroming, aggressive ramming) and tactical behaviors like resource denial (shooting player power-ups).
* **Dynamic UI & Systems:** Developed a comprehensive UI for ammo management, health tracking, and wave notifications, integrated with a scene management system for seamless game loops.
* **Boss Encounter Logic:** Designed and implemented a multi-phase boss fight featuring unique attack patterns, including proximity mines and homing missile salvos.
* **Performance & Polish:** Optimized the game for WebGL deployment and utilized Unity’s Post-Processing Stack (Bloom, Color Grading) to achieve a high-fidelity arcade aesthetic.

### 🏢 Office Scene: Level Design & Lighting
This project focuses on environmental storytelling and high-fidelity interior rendering within Unity. I transformed a conceptual space into a detailed professional office using **Filebase assets**, focusing on realistic set dressing and spatial flow. The project highlights my ability to work within the **High Definition Render Pipeline (HDRP)** to achieve AAA-quality visuals through sophisticated lighting and material setups. I also utilized **ProBuilder** for greyboxing and creating custom architectural meshes, ensuring the environment was both functional for gameplay and visually compelling.

[Medium Articles](https://medium.com/@sean.duggan/list/office-scene-4594b3187d56)

* **HDRP Lighting & Volumetrics:** Implemented advanced lighting solutions, including volumetric light fog, physically-based light intensities, and baked reflection probes to create a realistic indoor atmosphere.
* **Custom Modeling with ProBuilder:** Developed bespoke architectural elements and light-volume meshes using ProBuilder to supplement standard assets and refine the scene's geometry.
* **Environmental Storytelling:** Expertly placed props and organized "clutter" to create a realistic, lived-in office aesthetic, focusing on composition and player perspective.
* **Material & Texture Optimization:** Managed complex HDRP materials, including emissive textures for monitors and glass shaders for office partitions, to enhance surface realism.
* **Post-Processing Stack:** Fine-tuned global volume overrides such as Color Grading, Bloom, and Depth of Field to give the final render a polished, cinematic look.

### 🥽 VR Escape Room: Interactive Immersion
This project explores the design and implementation of a fully interactive Virtual Reality escape room built with Unity and the **XR Interaction Toolkit**. The focus was on creating tactile, intuitive interactions that bridge the gap between player intent and virtual physics. I developed a series of interconnected puzzles using **XR Socket Interactors** for key-and-lock mechanics, alongside custom **XRSnapInteractors** for complex object manipulation. To ensure player flow and prevent frustration, I engineered a multi-tiered **Hint System**—including in-universe "Gaze-activated" journals and a dynamic UI hint list—that gradually guides the player based on their progress and perspective.

[Medium Articles](https://medium.com/@sean.duggan/list/escape-room-37d6aac687ba)

* **XR Interaction Toolkit Mastery:** Leveraged the XR Interaction Toolkit to handle advanced locomotion (Teleport/Continuous) and complex object interactions, including custom hand-presence and haptic feedback.
* **Socket & Multi-Layer Logic:** Implemented XR Sockets with dedicated Interaction Layers to ensure only specific quest items (like keys or puzzle pieces) could trigger animations and state changes.
* **Physics-Based Control Systems:** Designed interactive "In-Game" controls such as functional levers, joysticks, and dials for mechanical puzzles, using dynamic events to map physical movement to game logic.
* **Context-Aware Hint System:** Scripted a "Gaze-to-Reveal" hint system and a persistent UI hint log that uses logic to provide progressively detailed clues, mimicking classic adventure game mechanics.
* **Environmental Animation & VFX:** Integrated Unity’s Animator with XR events to trigger environmental responses—such as opening doors or revealing hidden compartments—upon successful puzzle completion.

### 📱 Mobile AR: Dynamic Object Placement & Visualization
This project focuses on cross-platform mobile Augmented Reality (AR) development using **AR Foundation** and **ARCore/ARKit**. I developed a robust application that allows users to detect real-world planes and interactively place, move, scale, and rotate high-fidelity 3D assets (such as vehicles and turrets) within their physical environment. A key highlight of this project is the implementation of two distinct visualization scales: a **Desktop Mode** for tabletop examination of miniaturized models and a **Driveway Mode** for 1:1 life-sized visualization, allowing users to physically walk around and inspect salient features via informative proximity-based labels.

[Medium Articles](https://medium.com/@sean.duggan/list/unity-ar-686b0dceb815)

* **Advanced XR Interaction:** Integrated the **XR Interaction Toolkit** to support complex mobile gestures including tap-to-place (Raycasting), pinch-to-zoom (Scaling), and swipe-to-rotate.
* **Smart Placement Logic:** Engineered a custom Manager using C# Hashtables to enforce placement constraints, ensuring only one instance of a specific object exists in the scene at a time.
* **Contextual UI System:** Designed a responsive Unity UI with automatic layout groups that dynamically updates available actions (Examine, Remove, Reset) based on the current object selection.
* **Spatial Environmental Awareness:** Leveraged AR Plane Detection and AR Background Renderer features to ensure virtual objects grounded realistically on physical surfaces.
* **State Management:** Implemented a multi-mode system that transitions between "Placement" and "Examine" states, utilizing custom logic to handle location drift and scene resets for a smoother user experience.

### 🛸 Spaceship Cinematics: Timeline & Cinemachine
This project demonstrates the creation of a high-fidelity cinematic experience centered around a space transport vessel in the **High Definition Render Pipeline (HDRP)**. I utilized **Unity Timeline** to orchestrate complex sequences involving multiple tracks—including animation, audio, and VFX control—to bring the ship to life with custom thruster particles and environmental dust effects. A key technical focus was the integration of **Cinemachine** to handle dynamic camera transitions between external chase views and a detailed cockpit interior, alongside a "sleep mode" logic that automatically triggers a cinematic flyby sequence if no player input is detected.

[Medium Articles](https://medium.com/@sean.duggan/list/spaceship-project-eeea4e6f7ed1)

* **Timeline Orchestration:** Managed multi-track sequences using Animation, Activation, and Control tracks to synchronize spaceship movement with particle effects and layered ambient audio.
* **Cinemachine State Switching:** Implemented a Virtual Camera system that allows for seamless blending between gameplay-ready views and scripted cinematic shots.
* **HDRP Visual Polish:** Leveraged HDRP’s advanced rendering capabilities, including custom skyboxes and volumetric lighting, to achieve a professional sci-fi aesthetic.
* **VFX & Particle Integration:** Developed custom thruster effects using the Unity Particle Pack, upgrading textures for HDRP compatibility and utilizing Control tracks for precise timing during flight sequences.
* **Idle-Triggered Cinematics:** Scripted a logic-driven system that monitors user inactivity to transition the game into a "Cinematic Mode," showcasing the environment through curated camera paths.

### 🎯 Shooting Gallery: Logic & Interaction Lab
This project is a comprehensive study of modular game systems and interactive mechanics within a 3D shooting gallery environment. I utilized this build to experiment with diverse game logic patterns, specifically focusing on how to decouple object behavior from player input. By implementing **C# Interfaces**, I created a highly scalable interaction system where targets, environmental hazards, and UI elements respond to damage or triggers through unique, scriptable behaviors. The project also highlights advanced physics implementation, including projectile ballistics and destructible object logic.

[Medium Articles](https://medium.com/@sean.duggan/list/shooting-gallery-d746a1d9ec93)

* **Interface-Driven Architecture:** Leveraged `IDamageable` interfaces to allow a single shooting script to interact with a variety of targets—such as pop-up bipedal figures, rotating plates, and explosive canisters—without tight coupling.
* **Dual Shooting Systems:** Developed and compared both **Raycast** (instant hit) and **RigidBody Projectile** (physics-based) weapon systems to handle different gameplay requirements and visual feedback.
* **Dynamic Target Systems:** Scripted complex target behaviors, including path-following movement, randomized "peek" timers, and physics-based hit reactions using Unity’s animation and physics engines.
* **Centralized Game Manager:** Engineered a singleton-based Game Manager to track player performance, manage high scores via Persistent Data, and control the global game state (Start/Active/Game Over).
* **Audio & Visual Feedback Loops:** Integrated a tiered feedback system using Audio Spatialization and particle effects to provide immediate, satisfying confirmation for successful hits and environmental interactions.
