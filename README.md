# AI Based Frame Interpolation, Video Generation and Display System for WMS Services

## Problem Statement ID
1736

## Problem Statement Title
AI based frame interpolation, video generation and display system for WMS services

## Description
Develop a system that automatically generates videos using frame interpolation techniques given a WMS service that provides satellite imagery at regular intervals (e.g. every 30 minutes) and a bounding box. The AI based video generator should interpolate frames (for e.g. at every minute between 30 minutes) for smooth visualization of moving objects. This video should be displayed on an interactive browser-based map (using OpenLayers or Leaflet).

### Challenge
Frame interpolation of objects such as clouds which are deformable and even appear/disappear between frames. Overlaying videos on web-based map visualization libraries is straightforward on commercial libraries such as Mapbox. Developing the same functionality for modern open-source WebGIS libraries will be an added effort.

### Usage
Can be implemented for visualization on VEDAS/MOSDAC/BHUVAN.

### Users
WebGIS application developers and the end users of these applications.

### Available Solutions
Individual components are available, but a comprehensive and proven solution does not exist.

### Desired Outcome
The tool should be compatible with an OGC compatible WMS service. Should demonstrate video visualization overlay on an OpenLayers (> version 6) web map. Bonus points for utilization of on-device GPUs/NPUs available in modern desktop/mobile devices (not mandatory).

## Organization
Indian Space Research Organization (ISRO)