# Awesome-Remote-Play-Console-Streaming-Utilities

## Top Remote Play & Console Streaming Utilities Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Game Streaming, Console Remote Play, Self-Hosted Cloud Gaming Hosts & Low-Latency Client Apps*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Remote Play & Console Streaming**. These tools stream games from a PC or console to phones, tablets, TVs, handhelds, and other PCs—with an emphasis on low latency and controller support.



**Examples** include Sony Remote Play, Moonlight, Parsec, Chiaki / chiaki-ng, Sunshine, Steam Link, Rainway, Shadow, Boosteroid, GeForce Now, and related console tooling such as community PS5 projects.



**Open-source emphasis**: Self-hosted game streaming is led by open source. **Sunshine**, **Moonlight**, and **chiaki-ng** form the core stack for PC and PlayStation remote play. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[NVIDIA GeForce Now, Xbox Cloud Gaming, Amazon Luna](https://www.nvidia.com/en-us/geforce-now/)**  

  Cloud gaming services—stream from provider data centers rather than your own hardware.



- **[Shadow, Boosteroid, other cloud PC gaming services](https://shadow.tech/)**  

  Hosted Windows gaming PCs streamed to your devices—closer to a remote desktop for games.



- **[Sony PS Remote Play, Steam Link / Steam Remote Play](https://remoteplay.dl.playstation.net/)**  

  Official console and Steam client streaming—PS4/PS5 Remote Play and in-house Steam streaming to phones, TVs, and PCs.



- **[Parsec, Rainway (historical / related)](https://parsec.app/)**  

  Low-latency game and desktop streaming products—strong for multiplayer couch and remote setups (Parsec remains widely used).



- **[Other commercial remote-play and streaming apps](https://www.nvidia.com/en-us/geforce-now/)**  

  OEM and handheld companion apps that wrap GameStream-style or proprietary protocols.



## Open-Source GitHub Projects



### PC Game Streaming (Host + Client)



- **[Sunshine](https://github.com/LizardByte/Sunshine)**  

  Leading open-source self-hosted game stream host for Moonlight—low-latency capture and encoding on AMD, Intel, and NVIDIA GPUs (Windows, Linux, macOS).



- **[Moonlight](https://github.com/moonlight-stream)**  

  Open-source GameStream client family—stream from Sunshine (or legacy NVIDIA GameStream) to desktop, mobile, TV, and embedded clients.



- **[Moonlight Android / iOS / Qt / Embedded clients](https://github.com/moonlight-stream)**  

  Official and community Moonlight clients across platforms for the same Sunshine/GameStream protocol.



### PlayStation Remote Play Clients



- **[chiaki-ng](https://github.com/streetpea/chiaki-ng)**  

  Next-generation open-source PlayStation Remote Play client (successor to Chiaki)—PS4/PS5 streaming on Linux, Windows, macOS, Android, Steam Deck, and more (AGPL).



- **[Chiaki (original)](https://github.com/xhaikar/chiaki)**  

  Original open-source PS4/PS5 Remote Play client; largely in maintenance mode with active work continuing in chiaki-ng.



- **[Shimmer](https://github.com/slaughterhousesoftware/shimmer)**  

  Open native macOS client for Sunshine and PS5 Remote Play—Picture in Picture and DualSense-oriented features (builds on Moonlight/chiaki-ng protocol code).



- **[Orbit Play / jailbreak-oriented PS5 clients](https://github.com/search?q=PS5+Remote+Play+open+source)**  

  Community clients targeting specialized PS5 setups (e.g. jailbroken consoles); scope and requirements differ from stock Remote Play—verify legality and device state.



### Related Open Streaming & Display Tools



- **[Looking Glass](https://github.com/gnif/LookingGlass)**  

  Open extremely low-latency KVM FR frame sharing—stream a VM’s display to the host with near-local feel (great for dual-GPU / VFIO gaming setups).



- **[Wayland / PipeWire capture stacks](https://github.com/LizardByte/Sunshine)**  

  Open desktop capture paths used by Sunshine and other hosts on modern Linux.



- **[LibreGameStream / legacy protocol docs](https://github.com/moonlight-stream)**  

  Historical and protocol-related open work around NVIDIA GameStream-compatible streaming.



### Console Tooling (Related, Not Pure Streaming)



- **[AnyPS5](https://github.com/boykopovar/AnyPS5)**  

  Open tooling focused on porting PS5 executables toward Linux/Windows (relinker / library work)—adjacent to console ecosystems, not a Remote Play streamer. Use only with software you have rights to run.



### Additional Strong Open-Source Options



- **Self-hosted PC cloud gaming**: Sunshine (host) + Moonlight (client).

- **PlayStation from PC/Deck/phone**: chiaki-ng (official Remote Play alternative client).

- **VM gaming on the same machine**: Looking Glass.

- **macOS-native dual PC/PS5 client**: Shimmer.

- **Composable stacks**: Gaming PC → Sunshine → Moonlight on handheld/TV; or PS5 → chiaki-ng on Linux/Steam Deck.

- Commercial cloud services still lead when you do not want to own or power a host PC/console.



**Frameworks for building custom systems**:  

**Sunshine + Moonlight** for PC game streaming you control; **chiaki-ng** for PlayStation Remote Play on open platforms; **Looking Glass** for local VM passthrough display.  

Fully open remote-play stacks are production-quality for home and LAN use; internet streaming quality depends on your network and host hardware.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Stream only games and consoles you own and are licensed to use. Respect platform Terms of Service (Sony, Steam, NVIDIA, etc.). Projects aimed at jailbroken consoles or executable porting may have legal and warranty implications—know your local law.

- Open-source tools offer control and no subscription for self-hosted streaming. Cloud gaming services shift hardware and ops to the provider. Neither replaces a stable network and appropriate host GPU encode support.



---



**Made for PC and console gamers who want low-latency remote play without giving up ownership of the host.**  

Let's expand open game streaming while recognizing the convenience of official Remote Play apps and commercial cloud gaming platforms.
