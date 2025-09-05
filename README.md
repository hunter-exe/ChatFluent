# ChatFluent

**ChatFluent** is a peer-to-peer video calling app that helps people teach each other new languages through live face-to-face practice. Start a room, invite a partner, and practice speaking with real-time audio/video, text chat, and basic session controls.

## ✨ Features
- 1:1 video calls for language exchange (WebRTC)
- Room creation/join via shareable link
- Real-time signaling (Socket.IO)
- Mute/Unmute, camera on/off
- Basic chat and connection status
- Deployed on Render

## 🧱 Tech Stack
- **Frontend:** React (Vite) + TypeScript  + Tailwind 
- **Realtime:** WebRTC for media; **Socket.IO** for signaling
- **Backend:** Node.js + Express + Socket.IO server
- **Deployment:** Render (Web Service)
- **ICE/STUN:** Public STUN (e.g., Google) by default; optional TURN for NAT-heavy networks

> Note: This README assumes a common WebRTC + Socket.IO architecture which matches your app’s purpose. Your repo layout shows `backend/` and `frontend/` folders and a root `package.json` (confirmed on GitHub). Update any library names here if they differ in your code. (Repo structure: backend/, frontend/, package.json). 

## ✅ Prerequisites
- **Node.js ≥ 18** (LTS recommended)
- **npm** or **pnpm** or **yarn** (choose one)
- A modern browser with camera/microphone permissions
- (Optional) **TURN** server credentials if your users are behind strict NATs

## 🚀 Quick Start (Local)

```bash
# 1) Clone
git clone https://github.com/hunter-exe/ChatFluent.git
cd ChatFluent
