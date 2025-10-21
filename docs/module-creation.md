How to create your own module:

1) Write your module in python at modules folder
2) Edit server.py like this:
2.1) Import your module like this: from modules.yourfoldermodulename.moodulename import router as modulename_router
2.2) Put your module in PROTECTED_ROUTERS array in this format: (router_name, "/path", ["modulename"]),
2.3) Add your endpoint in endpoints module in API documentation
3) Launch your new server.py

