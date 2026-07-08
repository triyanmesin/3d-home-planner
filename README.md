# Blueprint3D

Open-source browser-based 3D floor planning application built with Three.js and TypeScript.

## Description

Blueprint3D is a modern 3D floor planner that allows users to create detailed floor plans in 2D and visualize them in realistic 3D directly in the browser. It includes furniture placement, support for custom 3D models, and easy project saving/loading.

This repository contains both the core library (`src/`) and a Next.js demo application (`app/`).

## Features

- 2D floor plan drawing with walls, corners and rooms
- Real-time 3D visualization using Three.js
- Furniture and interior object placement system
- GLB/GLTF model support with Draco compression
- JSON save & load functionality
- IndexedDB local storage
- Clean TypeScript architecture

## Tech Stack

- TypeScript
- Three.js + Draco
- Next.js (Demo App)
- Canvas API
- pnpm

## Getting Started

### Prerequisites
- Node.js 18+
- pnpm

### Installation

```bash
git clone https://github.com/triyanmesin/3d-home-planner.git
cd 3d-home-planner
pnpm install
