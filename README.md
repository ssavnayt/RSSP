# RSSP

### RSSP is a Roblox screen sharing project that allows you to share your server's screen with the Roblox Place client.

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
- [ ] Camera share (only server, broken)
- [ ] Mouse mover (not soon)
- [ ] WebStreamClient HTTP Method ([Documentation](https://create.roblox.com/docs/reference/engine/classes/HttpService#CreateWebStreamClient), if you can help, please create an issue)

How does it work?

Roblox servers send requests to the RSSP server via an API to display the screen.

How do I use this API manually?

Simply navigate to yourserver:2037/docs to see the available APIs.

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
3) Configure a port forwarding tool (if necessary), such as pinggy.io
4) Join my place: [Screen Test](https://www.roblox.com/games/98821705891412/Screen-Test) or publish it yourself and join (not available, only in [version 2](https://github.com/ssavnayt/RSSP/releases/tag/v2.0.0)).
5) Open the dashboard and connect to your IP address (the dashboard is in Russian, sorry).
6) Click "Connect."
7) Success.

> [!TIP]
> If you have any problems, please create an issue in this repository.

> [!CAUTION]
> Compatibility with Linux and macOS is not guaranteed. It may be broken on Linux and macOS. If not, please create a new issue.
