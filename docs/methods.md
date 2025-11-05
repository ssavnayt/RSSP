There is all roblox HTTP stream methods:
Polling (repeating HTTP request) - spamming server with requests to get image (1.0 - 2.1)
SSE (Server-Sent events) - server always sending a 1 frame to client (no raw bytes - no FPS) (2.1 - 2.2)
RawStream - server always sending a 1 frame to client (only raw bytes). Optimized (Soon)
