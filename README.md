
## 

In this project, a static webpage that lacks accessibility is given to be converted into a mobile-ready web application. The design must be responsive on different sized displays and accessible for screen reader use. It will also be added a service worker to begin the process of creating a seamless offline experience for the users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### How to Run?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

## Code Dependencies

1. [Udacity starter Code](https://github.com/udacity/mws-restaurant-stage-1)
2. [Normalize.css](https://necolas.github.io/normalize.css/)
3. [mapbox](https://www.mapbox.com)