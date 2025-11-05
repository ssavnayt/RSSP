# RSSP

### RSSP is a open-source Roblox screen sharing project that allows you to share your server's screen with the Roblox Place client.

<img width="886" height="421" alt="image" src="https://github.com/user-attachments/assets/c7e7d585-c7d1-4ed9-8e86-37ed04b6150d" />

Todo List:
- [x] Basic Screen Sharing
- [x] Keyboards and Mouse
- [x] Touchscreen
- [x] Error Reporting
- [x] GPU, CPU, and RAM Usage
- [x] Authentication System
- [x] Launching Applications
- [x] Shutdown system
- [x] Clipboard system
- [x] WebStreamClient SSE+base64 HTTP Method (v2.2 only)
- [ ] Camera share (only server, broken)
- [ ] Mouse mover (not soon)
- [ ] Port forwarding via pinggy or bore (.pub or .digital)
- [ ] WebStreamClient RawStream Method (server-side only, soon in 2.2.1+)

> [!CAUTION]
> Compatibility with Linux and macOS is not guaranteed. It may be broken on Linux and macOS. If not, please create a new issue.

INFO: [here](https://github.com/ssavnayt/RSSP/blob/main/docs/main.md)

How does it work?

Roblox servers send requests to the RSSP server via an API with Roblox SSE feature to display the server screen.

How do I use this API manually?

Simply navigate to yourserver:2037/docs to see the available API endpoints.

How to setup shared/config.py?

ss1 - compression value, in that value you are compressing screen resolution
Login and password from panel is:
AUTH_CONFIG = {
    "login": "yourlogin",
    "password": "yourpassword"
}

How to use this API?

1) Download the API
and configure the shared/config.py file
2) Run the API via `start.bat` or server.py
3) Configure a port forwarding tool (if necessary), such as pinggy.io (soon = api module to forward ports via pinggy or bore.pub or pore.digital)
4) Join my place: [Screen Test](https://www.roblox.com/games/98821705891412/Screen-Test) or publish it yourself and join (not available, only in [version 2](https://github.com/ssavnayt/RSSP/releases/tag/v2.0.0), or in version v2.2 (with old getscreenimg method).
5) Open the dashboard and connect to your IP address.
6) Click "Connect."
7) Success.

> [!TIP]
> If you have any problems, please create an issue in this repository!
