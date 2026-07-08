# Blueprint3D

Open-source browser-based 3D floor planning application built with Three.js and TypeScript.

## Description

Blueprint3D is a web-based application that allows users to design floor plans in 2D and visualize them in realistic 3D directly in the browser. It supports furniture placement, custom 3D models, and easy project management.

## Features

- Intuitive 2D floor plan drawing (walls, corners, rooms)
- Real-time 3D visualization powered by Three.js
- Furniture and interior object placement system
- Support for GLB/GLTF models with Draco compression
- JSON save/load functionality
- IndexedDB for local project storage
- Clean and modular TypeScript architecture

## Tech Stack

- **TypeScript**
- **Three.js** + Draco compression
- Canvas API
- GLTF/GLB model loading
- Deployable on Vercel

## Getting Started

### Prerequisites
- Node.js 18 or higher
- npm or pnpm

### Installation

```bash
git clone https://github.com/triyanmesin/3d-home-planner.git
cd 3d-home-planner
npm install
