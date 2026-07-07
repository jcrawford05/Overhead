# Overhead

A public web-based demo for a private Raspberry Pi flight tracker project.

This project visualizes nearby aircraft and renders selected flight information on a simulated RGB LED matrix display. It is designed as a portfolio-friendly companion to a private embedded systems project.

## Project Scope

This repository contains the public-facing web demo, system design writeup, and selected non-sensitive code examples.

The full Raspberry Pi hardware implementation is maintained separately in a private repository.

## Features

- Browser-based flight dashboard
- Simulated RGB LED matrix display
- Demo aircraft mode
- Optional live aircraft data mode
- Distance and bearing calculations
- Aircraft table and status cards
- GitHub Pages deployment
- Public/private architecture explanation

## Public vs Private

Public:

- Web dashboard
- UI components
- Demo data
- Generic geospatial calculations
- Architecture documentation
- Selected illustrative snippets

Private:

- Raspberry Pi service code
- ADS-B receiver integration
- RGB matrix hardware driver implementation
- Device deployment scripts
- Local configuration
- Hardware-specific optimizations

## Tech Stack

- React
- TypeScript
- Vite
- CSS
- GitHub Pages
- Optional OpenSky API integration

## Future Work

- Add more aircraft display modes
- Add richer map interactions
- Add historical demo playback
- Add configurable dashboard themes
- Connect the private hardware system to a sanitized public status feed
