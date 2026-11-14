# Nathan Rihet

Full Stack Engineer at Rokken, based in Osaka.
I work mainly with TypeScript and Python. Outside work, I build
real-time software: VR mods, a console port and games.

## Current work

At Rokken, I build web applications around computer-vision pipelines:
resumable video uploads, secure playback, human review of results
and access-controlled sharing.

My recent backend work includes a PostgreSQL-backed GPU scheduler
for sharing capacity between tenants and bounding how much work
is admitted. I also build background workflows with Temporal,
including retries, cancellation and failure recovery.

## Outside work

I maintain **[VRTRAKILL](https://github.com/NathanKneT/VRTRAKILL)**,
a mod that makes ULTRAKILL playable in VR through SteamVR, on the
game's current Steam version. Version 2.0 fixes the problems players
reported most in the original mod and adds PS VR2 adaptive triggers,
eye-tracked parries, a stabilized camera for streaming and optional
movement gestures. It starts in VR when SteamVR is running and in
flat mode otherwise, so it can stay installed. I handle it end to
end: hardware testing, signed releases and a one-click installer.
Built with C#, Unity, BepInEx and Harmony, with an AI assistant.

**[DuskOnVita](https://github.com/NathanKneT/DuskOnVita)** is an
unofficial PS Vita port built on Dusklight, the native build of the
Twilight Princess decompilation. The game's code runs natively on the
Vita's ARM CPU. I write the Vita side: a renderer that turns GX
commands into GXM, plus audio, input and memory. Performance work is
measured on the console: Hyrule Field went from 18 to 29 FPS, and
late audio buffers dropped from 29% to 0.2%.

I'm also building **[Kororo](https://nathanknet.itch.io/kororo-private-playtest)**,
a 3D puzzle game for the browser. Players push and pull blocks to
create a path through each level.

The simulation is deterministic and separate from rendering,
supporting undo and replay. Level solving and validation run in
Web Workers. A playable preview is available on itch.io;
the game is still in development.

## Selected work

- **[RTHT-3D](https://github.com/NathanKneT/RTHT-3D):**
  a webcam-based hand-tracking interface connecting Python,
  MediaPipe and Blender through UDP.
- **[Conversational Agents Course](https://github.com/NathanKneT/Master-AI-Chatbot-Course-2024):**
  seven practical workshops I designed and taught to about
  25 Master's students at Université Côte d'Azur, covering
  Python, FastAPI, LangChain and LLM applications.
- **[DocsRetriever](https://nathanglhf.com/engineering/docs-retriever/) (2024–2025):**
  a B2B document-search SaaS I built and launched with Next.js,
  NestJS, FastAPI and MongoDB. I continued maintenance and support
  through August 2025. The service is now offline.

Before Rokken, I worked at Capgemini and Cawita Technologies.
My freelance work ran from May 2024 to August 2025,
initially alongside my role at Capgemini.

## Technical focus

| Area | Technologies |
| --- | --- |
| Frontend | TypeScript, React, Next.js |
| Backend | Python, FastAPI, Node.js, NestJS |
| Data & workflows | PostgreSQL, MongoDB, Temporal |
| Interactive applications | Three.js, React Three Fiber, Web Workers |
| Games, VR & native | C#, Unity, BepInEx, Harmony, OpenVR, C++ |
| Cloud & delivery | AWS (Amazon S3, Amazon ECS), Azure, Docker, Terraform, GitHub Actions |
| Testing | pytest, Cypress, Vitest |

I also practice photography. My
[portfolio](https://nathanglhf.com/) brings my engineering
and photographic work together.

Happy to exchange ideas with other developers and independent creators.

[Portfolio](https://nathanglhf.com/) ·
[LinkedIn](https://www.linkedin.com/in/nathan-rihet/) ·
[Email](mailto:nathan.rihet06@gmail.com)
