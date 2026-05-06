# ShadeBase

A full-stack color palette management and accessibility system designed for creating, analyzing, and sharing color systems with a focus on usability and visual accessibility.

## Overview

ShadeBase is a MERN-based application that allows users to create, manage, and analyze color palettes while applying accessibility-focused transformations such as contrast evaluation, colorblind simulation, and blending mode visualization.

The system is designed as a design-tooling platform, combining color system management with real-time accessibility analysis.

---

## Features

- Create, edit, and manage color palettes
- Persistent user accounts with saved palette storage
- Detailed color inspection (HEX, RGB, derived metadata)
- Contrast ratio calculation for accessibility compliance
- Colorblind simulation modes for accessibility testing
- Blend mode previews for advanced color interaction visualization
- Export and sharing functionality for palettes and individual colors
- Social sharing integration (LinkedIn, Twitter)

---

## Tech Stack

- MongoDB
- Express.js
- React
- Node.js

---

## System Design

- User-based data model with persistent authentication
- Palette documents contain structured color arrays with computed metadata
- Accessibility tools operate on both individual colors and full palette datasets
- Real-time color transformations applied client-side for visualization
- Designed as a design utility system rather than a simple CRUD application

---

## Architecture Notes

- MERN stack full-stack architecture
- RESTful API for user and palette management
- Client-side computation for color analysis and accessibility tools
- Modular component structure for reusable color processing logic

---

## Deployment

- Frontend deployed via GitHub Pages
