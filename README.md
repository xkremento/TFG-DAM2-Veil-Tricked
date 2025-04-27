# TFG - Veil:Tricked

An innovative entertainment system that combines a multiplayer video game, a management API, and a companion mobile application.

## General Description

Veil is a comprehensive project consisting of three main components:

1. **VeilTricked**: A multiplayer video game developed in Unity
2. **Veil-API**: An API for managing users, friendships, and game matches
3. **Veil-Companion-App**: A complementary Android application

## Project Components

### 🎮 VeilTricked (Video Game)

[VeilTricked](aqui va el enlace al repo) is a multiplayer video game developed with the Unity engine that presents a "one versus all" dynamic. The main objective is:

- Find the player who acts as the "killer" before they eliminate the rest of the participants
- The killer must act stealthily to eliminate other players without being discovered
- The other players must collaborate to identify and stop the killer

This game mechanic promotes:
- Tension and suspense
- Logical deduction
- Cooperation between players
- High replayability thanks to the variety of possible situations

### 🔌 Veil-API

[Veil-API](https://github.com/xkremento/Veil-API) is a programming interface that serves as the backbone of the system, managing:

#### Users
- Registration and login
- User data retrieval
- Personal information updates
- Account deletion

#### Friendships
- Current friends listing
- Friendship request management (send, cancel, accept)
- Pending requests listing
- Friend removal

#### Game Matches
- Creation of new matches
- Match history queries (all or filtered by user)
- Game statistics storage

### 📱 Veil-Companion-App

[Veil-Companion-App](https://github.com/xkremento/Veil-Companion-App) is an Android application that complements the gaming experience by allowing users to:

- View their recent match history
- Manage their friends list
- Handle friendship requests
- Access their profile outside the main game

## System Architecture

```
┌─────────────────┐      ┌───────────────┐      ┌─────────────────┐
│   VeilTricked   │◄────►│    Veil-API   │◄────►│ Veil-Companion- │
│   (Unity Game)  │      │               │      │       App       │
└─────────────────┘      └───────────────┘      └─────────────────┘
```

The system is designed in a modular way, allowing the three components to interact with each other through the central API, maintaining data consistency and providing an integrated user experience.

## Technologies Used

- **VeilTricked**: Unity, C#
- **Veil-API**: Kotlin, Spring Boot, MySQL
- **Veil-Companion-App**: Kotlin, Jetpack Compose, Retrofit

## Installation and Setup

For each component, visit the corresponding GitHub links:

- Video game: [aqui va el enlace al repo](aqui va el enlace al repo)
- API: [https://github.com/xkremento/Veil-API](https://github.com/xkremento/Veil-API)
- Android App: [https://github.com/xkremento/Veil-Companion-App](https://github.com/xkremento/Veil-Companion-App)

## Team

- [Álvaro Fernández López](https://github.com/xkremento)
- [Ahmed Hassan Khamis](https://github.com/AhmedHassanKhamis)
- [Kida Garcia](https://github.com/KidaGarcia)