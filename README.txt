TOUCHLINE LEGEND — 3D MATCH STARTER

Open index.html in a modern browser with internet access. This build uses Three.js from a CDN, so it needs a connection to load the 3D engine.

CONTROLS
- Touch/drag the round pad in the bottom-left to move.
- PASS: pass to a nearby teammate when close to the ball.
- SHOOT: attempt a shot when close to the ball.
- SPRINT: hold to run faster (uses energy).
- SWITCH: swap control position with the teammate closest to the ball.
- Keyboard fallback: WASD / arrow keys to move, E to pass, Space to shoot, Shift to sprint.

CURRENT BUILD
- Real-time 3D scene rendered with Three.js.
- Football pitch, markings, goals, stadium stands, lights, simplified 3D players and ball.
- Basic player movement, pass/shot actions, ball motion, simplified team movement, scoreboard and match clock.
- Fictional teams. Match AI and physics are prototype-level.

IMPORTANT LIMITATIONS
- This is a web-based 3D prototype, not an App Store app.
- It requires network access to load Three.js. Some iOS in-app preview contexts may block module imports; use Safari or a local web server.
- A robust, polished game needs proper animated player models, animation blending, goalkeeper/defender AI, collision handling, offside/fouls, menus, save data, accessibility, sound, QA and performance profiling.
- Online multiplayer is not implemented.

PATH TO APP STORE
1. Prototype gameplay and controls.
2. Move the game into Unity for iOS packaging, asset pipeline, animation tooling, touch UI and device profiling.
3. Add original/licensed models, animations, audio and stadium assets.
4. Build career progression and persistent saves.
5. For multiplayer, implement a secure authoritative backend, matchmaking, reconnect flow and anti-cheat.
6. Test on real iPhones and iPads; optimise thermals, battery, frame rate and accessibility.
7. Use TestFlight for external beta testing, prepare App Store metadata/privacy disclosures, and submit for review. Apple Developer membership is normally needed for distribution.
