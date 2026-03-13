# Ipchat

What's built in this demo:

Landing page — shows your auto-generated anonymous ID (e.g. GhostViper42), create room or join by IP
Create Room — generates a random IP-style room code instantly
Join Room — validates and enters any IP-format room code
Chat UI — cyberpunk terminal aesthetic, typing indicators, timestamps, left/right bubbles, copy room IP button
Simulated user — a bot joins and chats to demo the experience

To make this real (multi-user), you'd need a backend:
The demo is frontend-only. For actual real-time chat between different devices, you'd add:

Node.js + Socket.io server — handles WebSocket connections per room IP
Room registry — maps IP codes to sets of connected sockets
Deploy — on Railway, Render, or a VPS (₹500–1000/month)
