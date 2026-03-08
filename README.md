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
- **Linux & Windows client**
- **Standalone client** — no .NET runtime required on the target machine
- **x64 only**
- **And many more ** - See COMMANDS.pdf
- The interface might look familiar 😉

## Commands

```
See "Commands.pdf"
```

> [!NOTE]
>
> Please note that this software is still in development and may contain bugs.

## UI 

![Win](https://private-user-images.githubusercontent.com/42241901/559923024-a46d1836-b916-4e81-aaab-75d7ccd44727.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzI5ODE4ODQsIm5iZiI6MTc3Mjk4MTU4NCwicGF0aCI6Ii80MjI0MTkwMS81NTk5MjMwMjQtYTQ2ZDE4MzYtYjkxNi00ZTgxLWFhYWItNzVkN2NjZDQ0NzI3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAzMDglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMzA4VDE0NTMwNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg4MDk5ZmJjNDk4MDZkZjkzMzk4YWIwOGQ2NGM0YjBlMTg2MjA5NDI4YzEzMWViYzcwM2Y3MzdkZTljNThjNDkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.ZN6rX7uVt_Fr9VPrOX0xio_mReJDGZJ2H4yAsUuorLU)
![Lin](https://github.com/arsium/VoidHexed_Monitor/blob/main/VoidHexedBetaLin.png?raw=true)
![WinLin](https://github.com/arsium/VoidHexed_Monitor/blob/main/WindowsAndLinuxClient.png?raw=true)
