### Rust Developer | GameDev | ECS

I'm an independent developer interested in software architecture, game development, and building tools for complex interactive systems.

My primary language is **Rust**. I mostly work with game-related technologies, experiment with custom tooling, and explore ways to build systems that are both flexible and scalable.

## What I work with

- **Rust** — my primary development language.
- **Bevy** — game development, ECS-based architecture, rendering, and editor tooling.
- **HTML, CSS, JavaScript** — interactive web applications and interfaces.
- **SVG** — procedural graphics and interface elements.
- **Rhai** — scripting and extensibility in Rust-based projects.
- **Cargo & crates.io** — Rust project management and ecosystem.

I'm also familiar with Java and can work with C# when needed.

## Projects

### Purple Print
A voxel-based editor for creating modular 3D game objects.

The editor uses silhouettes drawn from three projections to generate voxel models. It also supports modular attachment points, scripting through Rhai, editing tools, and exporting objects into my own custom format (.mpp).

**Technologies:** Rust, Bevy, egui, Rhai.

*Work in Progress.*

### Nebros RS
A virtual analog synthesizer inspired by Soviet audio equipment (specifically the "Polivoks"). It emulates the imperfections of analog circuitry and offers a flexible architecture for real-time sound processing.

- **DSP and Synthesis:** Features 4 oscillators, a state-variable filter, an ADSR envelope, and 4 voice-handling modes (mono, legato, polyphony with voice stealing, and portamento).
- **Physical Modeling:** Advanced spring reverb emulation with 13 parameters, including procedural modeling of rust, metal fatigue, and temperature-induced drift.
- **Architecture:** Supports two deployment modes: as a standalone desktop application or as a module for a custom plugin host (Dansel Engine), allowing the synthesizer to be loaded as a `.dll` file within a DAW.

**Technologies:** Rust, egui, cpal, Digital Signal Processing (DSP).

### Guitar Digitization Builder
A web-based tool for learning, visualizing, and procedurally generating fingerings on a guitar fretboard.

- **Algorithms:** Includes a proprietary algorithm for finding and evaluating chord fingerings (accounting for barre chords, open strings, finger span, and base fret position), as well as a scale builder that supports custom interval sequences.
- **Interactivity:** Features a built-in synthesizer (via the Web Audio API) for auditioning notes, dynamic SVG visualization with scale-degree highlighting, a responsive design, and full localization (RU/EN).

**Technologies:** HTML, CSS, JavaScript, Web Audio API, SVG.

### Other experiments

I also work on procedural world generation, simulation systems, and custom game-development tools.

Some of these experiments include a procedural 3D-game pet-project and a experimental custom game engine.
