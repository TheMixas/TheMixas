# Hey, I'm Gustas 👋
 
Final-year Computer Science student at Swansea University (BSc Hons, 2024–2027), looking for graduate software engineering roles from summer 2027. I like programming things from scratch to figure out the black box.

**Languages:** C++, C, C#, Java, TypeScript/JavaScript, SQL

**Tools:** Linux, Docker, Git, CMake, PostgreSQL, MySQL, Redis
 
## What I'm working on
### Full-stack projects
**[Ryklys](https://github.com/TheMixas/ryklys)** · [live demo](https://ryklys-gustas.spaincentral.cloudapp.azure.com) - A live streaming platform built from scratch. Custom C++ HTTP and WebSocket server with epoll, WebRTC ingest, FFmpeg transcoding to HLS, Redis pub/sub chat, PostgreSQL. React + TypeScript frontend. No off-the-shelf backend frameworks. Deployed with Docker and Caddy on an Azure VM.

**[Typefaster](https://github.com/TheMixas/Typefaster)** · [live demo](https://typefaster-gustas.duckdns.org) - Real-time multiplayer typing race. The Node.js server runs each lobby as a state machine (theme vote -> countdown -> race -> results) and streams every player's progress and WPM over Socket.IO several times a second. React client, MySQL for accounts and race history.

**[Gossip](https://github.com/TheMixas/Gossip)** · [live demo](https://gossip-gustas.duckdns.org) - Social micro-blogging site: posts with images, reposts, comments, likes, friend requests and real-time chat over Socket.IO. React + Node.js/Express + MySQL, JWT auth in HttpOnly cookies, image storage on S3 or local disk.

### Operating System projects
**[Vilkas-x86-cpp](https://github.com/TheMixas/Vilkas-x86-cpp)** - 64-bit x86 kernel written from scratch in C++: long mode boot, paging, a GDT and IDT, and exception handling with register and page-fault reporting. Currently working on hardware interrupts and a physical memory allocator.


### Low-latency projects
**[itch-parser](https://github.com/TheMixas/itch-parser)** - Nasdaq ITCH 5.0 binary protocol parser. Parses 268M messages from a full trading day at 170M msg/sec. Zero-copy mmap, SoupBinTCP framing, all message types. Foundation for an in-progress limit order book.

### Open source
**[LLVM #205520](https://github.com/llvm/llvm-project/pull/205520)** - Fixed a crash in the PlaceSafepoints pass: an invalid `gc.safepoint_poll` now reports a usage error instead of crashing, with lit tests for each case. Approved, waiting on merge.
 
## What I'm interested in

Everything programming related, but really appreciate systems programming, low-latency networking, high-frequency trading infrastructure, and anything where performance matters at the metal level.

## Other projects

**[jewel-thief](https://github.com/MaxMiddletonDev/Jewel-Thief-Coursework)** — Tile-based puzzle game 
built in Java/JavaFX as a 9-person university team. Designed the screen management 
system and co-developed the core game loop.

## Get in touch
 
**Email:** rovegustas@gmail.com
 
