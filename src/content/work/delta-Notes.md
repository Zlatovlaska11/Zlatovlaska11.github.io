---
title: Delta-Notes-Endpoint
publishDate: 2024-03-23
img: /assets/stock-3.jpg
img_alt: Delta Notes API Endpoint logo
description: |
    A Rust-based API server for managing and serving educational presentations
tags:
  - Web API
  - Rust
  - Education
  - File Management
---

## Delta-Notes-Endpoint

**Delta-Notes-Endpoint** is a specialized Rust-based API server designed to serve educational PowerPoint presentations on demand. Built with Rocket and SurrealDB, this application enables authenticated access to course materials through a structured endpoint system.

### Features

* **User Authentication**: Secure login and registration system with JWT token validation
* **Course Management**: Organized file structure for different academic courses
* **PowerPoint Presentation Delivery**: Direct serving of PPTX files with viewer integration
* **SurrealDB Integration**: Modern database backend for user credential storage
* **Cross-Origin Resource Sharing**: Configured for seamless frontend integration

### Technical Architecture

The system utilizes Rocket.rs for routing, SurrealDB for data persistence, and employs a modular file handling system to navigate educational content organized by course. The application is structured to support both local development and deployment through Shuttle.rs.

### Getting Started

#### Prerequisites

* Rust installed (latest stable version)
* Cargo, Rust's package manager
* Local storage for educational presentation files
