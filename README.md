# Nathan Rihet

Full Stack Engineer in Osaka. I build web apps and backend services in TypeScript
and Python, lately around computer vision and GPU workloads. Outside work, I build
real-time software: VR mods, a console port and games.

## Experience

**Rokken** · Full Stack Engineer · Osaka · 2025–now  
The full-stack app around video-analysis pipelines: resumable uploads, secure playback,
human review and access-controlled sharing. I designed a PostgreSQL-backed GPU scheduler
with fair sharing between tenants and bounded admission, and build Temporal workflows
for retries, cancellation and recovery. I also look after test coverage and CI
(pytest, Cypress, GitHub Actions).

**Freelance** · Full Stack Developer · 2024–2025  
Client web apps, plus [DocsRetriever](https://nathanglhf.com/engineering/docs-retriever/),
a B2B document-search SaaS I built and ran (Next.js, NestJS, FastAPI, MongoDB, vector search).
Now offline.

**Capgemini** · Software Engineer · 2024–2025  
Enterprise generative-AI apps with React, FastAPI and LangChain. Moved services from
Flask to FastAPI (p95 from 500 to 200 ms), built hybrid document retrieval and automated
Azure deployments with Docker and Terraform.

**Cawita Technologies** · Full Stack Developer · 2022–2023  
Full-stack apps and REST APIs on Node.js, Express, Angular and MongoDB.

**Université Côte d'Azur** · Instructor · 2024–2025  
Designed and taught [seven workshops on conversational agents](https://github.com/NathanKneT/Master-AI-Chatbot-Course-2024)
to more than 20 Master's students, covering Python, FastAPI, LangChain and LLM applications.

## Latest: Cloudpunk VRevival

<img src="https://github.com/NathanKneT/CloudpunkVRevival/raw/main/media/cockpit.gif" width="480" alt="Flying the HOVA from its cockpit in Cloudpunk VRevival">

[Cloudpunk VRevival](https://github.com/NathanKneT/CloudpunkVRevival) puts Cloudpunk, a Unity 2018 IL2CPP game
that never shipped with VR, in a headset. A BepInEx 6 preloader patch turns on the engine's OpenVR support,
then the mod drives the game's own cameras from the headset, moves the UI onto a floating panel and feeds
a virtual gamepad into the game's input system. On top of that: a cockpit you fly with your hands,
first person on foot, and PS VR2 adaptive triggers and eye select.

I work on it with AI coding agents: they take features on parallel branches, I set the design and test
in the headset, and an in-game test harness replays scripted scenarios on SteamVR's null headset driver
to check each change.

## Side projects

| Project | What it is | Built with |
| --- | --- | --- |
| [VRTRAKILL](https://github.com/NathanKneT/VRTRAKILL) | VR mod for ULTRAKILL on its current Steam build, with PS VR2 adaptive triggers and eye-tracked parries | C#, Unity, BepInEx, Harmony, OpenVR |
| [DuskOnVita](https://github.com/NathanKneT/DuskOnVita) | Native PS Vita port of the Twilight Princess decompilation, with its own GX-to-GXM renderer (18 → 29 FPS on Hyrule Field) | C++, GXM, VitaSDK |
| [Kororo](https://nathanknet.itch.io/kororo-private-playtest) | 3D puzzle game for the browser, with a deterministic simulation, undo and replay. Playable preview on itch.io | TypeScript, Three.js, React Three Fiber, Web Workers |
| [RTHT-3D](https://github.com/NathanKneT/RTHT-3D) | Webcam hand tracking that drives a Blender scene in real time (demo: 343K views) | Python, MediaPipe, OpenCV, UDP |

## Stack

| Area | Technologies |
| --- | --- |
| Frontend | TypeScript, React, Next.js |
| Backend | Python, FastAPI, Node.js, NestJS |
| Data & workflows | PostgreSQL, MongoDB, Temporal |
| AI | LangChain, RAG, LLM applications, computer vision, AI coding agents |
| Interactive & 3D | Three.js, React Three Fiber, Web Workers |
| Games, VR & native | C#, Unity, BepInEx, Harmony, OpenVR, C++ |
| Cloud & delivery | AWS (Amazon S3, Amazon ECS), Azure, Docker, Terraform, GitHub Actions |
| Testing | pytest, Cypress, Vitest |

[Portfolio](https://nathanglhf.com/) · [LinkedIn](https://www.linkedin.com/in/nathan-rihet/) · [Email](mailto:nathan.rihet06@gmail.com)
