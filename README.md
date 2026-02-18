# Void Hexed Monitor

<p align="center">
  <img src="https://raw.githubusercontent.com/arsium/VoidHexed_Monitor/refs/heads/main/VHM.png" alt="description" />
</p>

The first cross-platform Remote Access Tool built entirely in C#.

## Goals

Void Hexed Monitor was born from a simple question: is it possible, with  modern .NET, to build a fully cross-platform RAT — both the server UI  and the client? The answer turned out to be yes.

The project will remain closed-source (binaries only) until further notice, and may be commercialized in the future.

## Features 

- **TLS 1.3** — fully self-contained, no external dependency
- **Builder & compression** — generate and pack client payloads directly from the server
- **Auto-reconnect** — client automatically re-establishes connection if lost
- **Cross-platform server** — UI runs on both Windows and Linux
- **Linux client** — currently supported (Windows client in progress)
- **Standalone client** — no .NET runtime required on the target machine
- The interface might look familiar 😉

## Commands

```
Default passwords used at certificate generation:

ca : password123
server : "password456
client : password789

server <start> <server_password> <ca_password> <port>
ex : server start password456 password123 5555

build <remote_ip> <remote_port> <client_password>
ex : build 192.168.1.2 5555 password789

select <client_hwid>
ex : select 9D73395970DDA6B40F3B

list selected
OR
list
```

> [!NOTE]
>
> Please note that this software is still in development and may contain bugs.

## UI 

![Win](https://github.com/arsium/VoidHexed_Monitor/blob/main/VoidHexedBeta.png?raw=true)
![Lin](https://github.com/arsium/VoidHexed_Monitor/blob/main/VoidHexedBetaLin.png?raw=true)
