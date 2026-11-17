# Varro Voice Station

**Status:** Planned  
**Technologies:** ESP32 · Embedded C/C++ · Wi-Fi · I²S Audio · Network Streaming

## Overview

Varro Voice Station is a standalone, network-connected voice interface for the Varro assistant. I am designing it for fixed locations where a microphone and speaker can communicate directly with Varro's voice services without requiring a phone or Bluetooth companion app.

The **Varro** name honors Marcus Terentius Varro, a Roman scholar associated with broad, organized knowledge.

## Key Design Choices

- **Direct network connection:** Stream audio and control messages to the Varro Voice Server over the local network.
- **Local activation:** Explore wake-word detection and voice-activity detection to limit unnecessary audio transmission.
- **Lightweight endpoint:** Keep transcription, speaker verification, and speech synthesis on backend services.
- **Stationary design:** Favor reliable connectivity and straightforward power delivery over battery portability.

## Roadmap

- [ ] Select the controller, audio components, and network interface.
- [ ] Prototype local audio capture, playback, and activation.
- [ ] Implement streaming sessions with the Voice Server.
- [ ] Integrate response playback and device state handling.
- [ ] Evaluate speech latency and stability in typical room conditions.

## Usage

### Requirements

### Setup

### Configuration

### Operation
