# VELOXIS Racing Hub - Official Changelog

## [V0.19.1] - 2026-04-09
### First Public Release - "Pre-Alpha"
This is the official public debut of the VELOXIS Racing Hub, a comprehensive bridge between Assetto Corsa and a global competitive ecosystem.

#### Core Features
- **Real-Time Telemetry**: High-frequency UDP data capture for lap times, sector splits, and vehicle telemetry.
- **Validity Satellite (Lua)**: Integrated Lua application for Assetto Corsa that monitors track limits and collisions in real-time.
- **Sidecar Shared Memory**: 20Hz Shared Memory reader for UTC-synchronized validity verification and anti-cheat.
- **Advanced Anti-Cheat**: 
  - Input Analysis (Detection of macros/robotic steering).
  - UTC Drift Monitoring (Prevention of time-scale manipulation).
  - Shared Memory verification.
  - Car & Track Hash verification.
- **Global Leaderboards**: Discord-synced leaderboards with automated lap verification and trust-gated uploads.
- **In-Hub Video Archive**: Integrated lap recording and history management.
- **Driver Profiles**: Track individual stats, trust scores, and global standings.
- **Managed Mod Installer**: One-click installation for verified cars and tracks.
- **Glassmorphic UI**: Premium, high-performance interface with real-time HUD and status indicators.

#### Recent Improvements (Audit v0.19.1)
- **Architecture Overhaul**: Migrated to a scalable dual-service hierarchy (`/hotlap` and `/telemetry`).
- **Repacked Nano Installer**: Re-engineered the 2MB bootstrapper for 100% reliability on fresh Windows installations.
- **API Synchronization**: Unified versioning and download metadata across the entire stack.
- **Contact Detection**: Enhanced Lua satellite to detect car-to-car and car-to-object collisions.

---

## [V0.1.0 - V0.16.0] - Alpha Development
- **Internal Builds**: Developed the core UDP engine, shared memory sidecar, and initial Discord integration.
- **Design Iteration**: Transitioned from basic HTML/CSS to a high-end React/Next.js design system.
