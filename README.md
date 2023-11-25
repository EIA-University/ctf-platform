# ![](https://github.com/CTFd/CTFd/blob/master/CTFd/themes/core/static/img/logo.png?raw=true)

![CTFd MySQL CI](https://github.com/CTFd/CTFd/workflows/CTFd%20MySQL%20CI/badge.svg?branch=master)
![Linting](https://github.com/CTFd/CTFd/workflows/Linting/badge.svg?branch=master)
[![MajorLeagueCyber Discourse](https://img.shields.io/discourse/status?server=https%3A%2F%2Fcommunity.majorleaguecyber.org%2F)](https://community.majorleaguecyber.org/)
[![Documentation Status](https://api.netlify.com/api/v1/badges/6d10883a-77bb-45c1-a003-22ce1284190e/deploy-status)](https://docs.ctfd.io)

## What is CTFd?

CTFd is a Capture The Flag framework focusing on ease of use and customizability. It comes with everything you need to run a CTF and it's easy to customize with plugins and themes.

![CTFd is a CTF in a can.](https://github.com/CTFd/CTFd/blob/master/CTFd/themes/core/static/img/scoreboard.png?raw=true)


## Install

1. Install dependencies: `pip install -r requirements.txt`
   1. You can also use the `prepare.sh` script to install system dependencies using apt.
2. Modify [CTFd/config.ini](https://gitlab.com/juanmusic1/ctf-platform/-/blob/main/CTFd/config.ini) to your liking.
3. Use `python serve.py` or `flask run` in a terminal to drop into debug mode.

You can use the auto-generated Docker images with the following command:

`docker run -p 8000:8000 -it ctfd/ctfd`

Or you can use Docker Compose with the following command from the source repository:

`docker-compose up`

Check out the [CTFd docs](https://docs.ctfd.io/) for [deployment options](https://docs.ctfd.io/docs/deployment/installation) and the [Getting Started](https://docs.ctfd.io/tutorials/getting-started/) guide

## Live Demo

https://semiillerosegeia.info/

```

## Credits

- Logo by [Laura Barbera](http://www.laurabb.com/)
- Theme by [Christopher Thompson](https://github.com/breadchris)
- Notification Sound by [Terrence Martin](https://soundcloud.com/tj-martin-composer)
- EIA theme by Cybersecurity investigation
