# Forge Web

**AI-Native Streaming Platform Visualizations**

Forge Web is the visualization and overlay layer for Forge Studio - an AI-native streaming platform that makes invisible AI development processes visible through automated visualization, real-time analysis, and intelligent cinematography.

## Overview

This repository contains the web-based components for streaming AI development work:

- **3D Knowledge Graph**: Interactive visualization of AI context embeddings from AIDIS/Mandrel database
- **HUD Overlays**: Real-time data displays for OBS browser sources
- **Spindle Viewer**: LLM reasoning visualization from API responses
- **Context Carousel**: Semantic search results display
- **Live Analytics**: Charts and graphs for development metrics

## Tech Stack

- **Visualization**: Three.js for 3D rendering
- **Graphics**: Chart.js for live graphs
- **Real-time**: WebSocket connections to backend
- **Data Source**: PostgreSQL + pgvector (aidis_production database)
- **Integration**: OBS browser sources

## Project Structure

```
forge-web/
├── index.html              # Main 3D embeddings visualization
├── assets/                 # Static assets and resources
├── data/                   # Data files and exports
├── obs-overlays/          # OBS browser source overlays
└── debug-images/          # Development and testing assets
```

## Features

### 3D Embeddings Visualization
Interactive 3D rendering of AI context embeddings stored in the Mandrel vector database, providing a visual representation of knowledge clustering and relationships.

### OBS Integration
Browser source overlays designed for clean, professional streaming presentation:
- Translucent tiles with proper spacing
- Real-time data updates via WebSockets
- Automated cinematography support

### Real-time Analysis
Live visualization of:
- Git change narration
- Commit activity metrics
- API call patterns
- Context retrieval patterns

## Related Projects

- **Forge Studio**: Complete streaming infrastructure using OBS
- **AIDIS/Mandrel**: PostgreSQL + pgvector context management system
- **SIRK Lab**: Single Instance Recursive Knowledge experiments

## Brand

Part of **RidgetopAI** - Making AI development processes visible and engaging.

---

**Status**: Active Development
**Database**: aidis_production (PostgreSQL + pgvector)
**Purpose**: Transform invisible AI work into watchable, informative streams
