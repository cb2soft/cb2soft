Hey there, I'm Cevat 👋
Software Developer | C# Enthusiast | Game Dev

I love building things with C# — from enterprise automation tools to multiplayer games.

C#.NETUnity

🧑‍💻 About Me
🔭 I'm currently working on enterprise automation tools and a multiplayer game built with Unity
💬 My primary language is C# — I use it for everything from console apps to game development
🎮 Passionate about game development, networking, and physics-based mechanics
🌍 Based in Turkey
⚡ Fun fact: I've implemented CS:GO-style bunnyhop physics from scratch in Unity
🛠️ Tech Stack
Category	Technologies
Languages	C#
Frameworks	.NET 8Unity
Networking	MirrorSteamworks.NET
Integrations	CargoWiseREST APIGraphQL
Tools	GitVisual StudioWindows
📌 Featured Projects
💱 Exchange Rate Importer
Automated daily exchange rate fetcher & CargoWise One importer for multi-country logistics operations.

A .NET 8 console application that fetches live buy/sell exchange rates from central banks and financial institutions across 5 countries (Turkey, India, UAE, Australia, Vietnam), then automatically imports them into CargoWise One via the Native XML API.

Key Highlights:

🌐 Multi-source data collection: XML feeds, HTML scraping, REST APIs, GraphQL (with OAuth2)
📊 Dual-server targeting (Test / Production) with environment variable-based config
🔄 Business-day logic handling (weekend/holiday awareness)
📝 Comprehensive logging with audit trails
⏰ Windows Task Scheduler integration for full automation
Tech: .NET 8 · HttpClient · XML Serialization · HTML Parsing · GraphQL · OAuth2 · GZip · CargoWise Native XML API

🎮 Multiplayer Party Game (In Development)
A multiplayer FPS party game with multiple game modes, built with Unity + Mirror + Steamworks.

An online multiplayer game featuring unique party game modes like Deathrun and Speedrun, with Steam-based matchmaking and lobby systems.

Key Highlights:

🏗️ Modular Architecture: PlayerController split into 6 partial classes (Movement, Weapon, Network, Interaction, Audio) — 1800+ lines of organized code
🎯 Deathrun Mode: Runner vs Killer teams, 11 unique trap types, state machine-driven rounds, voting system
⚡ Speedrun Mode: CS:GO-style bunnyhop & air-strafing, surf mechanics, ice physics, portals with momentum preservation
🔫 Full Weapon System: ScriptableObject-based, FPS+TPS dual models, ADS, procedural recoil, melee combat
🌐 Networking: Mirror framework with Steamworks.NET transport, SyncVar/Command/RPC architecture, heartbeat system with disconnect detection
🗺️ 6+ Maps across different themes (Desert, Space, Winter)
🪤 11 Trap Types: Moving platforms, rotating obstacles, fans, fire bridges, glass paths, death zones, and more
Tech: Unity · C# · Mirror Networking · Steamworks.NET · URP · Rigidbody Physics · ScriptableObjects
