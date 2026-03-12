# MAGIK-BOXA
A mobile app for weddings, parties, and community events with music, themes, and live effects.
# Celebration App – Full Specification (Clean Version)

## Overview
A mobile application designed to create a joyful, colorful, music-driven experience for weddings, parties, and community events. The app includes a song library, video player, live effects, themes, queue system, and dynamic backgrounds.

## Core Features
- Song Library
- Video Player
- Live Effects
- Themes (Wedding, Party, Community, Calm)
- Queue System
- Event Selection
- Dynamic Backgrounds
- User Profile

## Tech Stack
- Flutter or React Native
- Node.js Backend
- Firestore or MongoDB
- Cloud Storage for Media
- WebSocket for real-time sync

## Screens
### Splash
- Logo
- Live background
- Auto transition

### Home
- “Choose Event”
- “Popular Songs”
- Active Theme
- Live background

### Events
- Event cards (Wedding, Party, Community, Calm)
- Start Event button

### Song List
- Song cards
- Categories
- Search
- Play button
- Add to Queue button

### Player
- Fullscreen video
- Lyrics
- Effects
- Theme visuals
- Next button
- Add to Queue

### Queue
- Song list
- Drag to reorder
- Delete
- Play

### Profile
- User info
- History
- Settings

## Modules
### Song Module
- Load songs
- Search
- Filter
- Categories

### Player Module
- Video playback
- Preloading
- Effect sync
- Auto-next

### Queue Module
- Add
- Remove
- Reorder
- Save

### Theme Engine
- Wedding Theme
- Party Theme
- Community Theme
- Calm Theme

### Animation Engine
- LightPulse
- ColorBurst
- WeddingGlow
- DynamicBackground

## API
GET /songs  
GET /songs/{id}  
POST /queue  
DELETE /queue/{id}  
GET /themes  
GET /events  

## Data Models
### Song
id  
title  
artist  
category  
videoUrl  
imageUrl  
tags[]

### Event
id  
name  
imageUrl  
theme

### Queue
userId  
songs[]

## Folder Structure (Skeleton)
src/
  screens/
    Home/
    Events/
    SongList/
    Player/
    Queue/
    Profile/
  components/
    SongCard/
    EventCard/
    QueueItem/
    ThemeSwitcher/
  themes/
    WeddingTheme/
    PartyTheme/
    CommunityTheme/
    CalmTheme/
  animations/
    LightPulse/
    ColorBurst/
    WeddingGlow/
    DynamicBackground/
  api/
    songs.js
    queue.js
    themes.js
    events.js
  models/
    Song.js
    Event.js
    Queue.js
  utils/
    helpers.js
    formatters.js

## Development Roadmap
### Sprint 1
- Base screens
- Song library
- Basic API
- Data models

### Sprint 2
- Player module
- Queue module
- Theme engine

### Sprint 3
- Effects
- Animations
- Dynamic backgrounds

### Sprint 4
- QA
- Performance improvements
- Final polish
- APK build

## Build Instructions
### Flutter
flutter create celebration_app

### React Native
npx react-native init CelebrationApp

## AI Build Command
Build the full mobile application according to the complete specification. Use Flutter or React Native. Create all screens, components, navigation, API handlers, data models, themes, and animations. Follow the folder structure exactly as defined. Implement the Song Module, Player Module, Queue Module, Theme Engine, and Animation Engine.

