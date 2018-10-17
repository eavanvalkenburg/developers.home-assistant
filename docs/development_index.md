---
title: "Starting with Development"
sidebar_label: Introduction
---

Home Assistant is built from the ground up to be easily extensible using components. Home Assistant uses [Python 3](https://www.python.org/) for the backend and [Polymer (Web components)](https://www.polymer-project.org/) for the frontend.

Home Assistant is open-source and licensed under [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0). Here are links to the source:

 - [home-assistant](https://github.com/home-assistant/home-assistant): Python server backend.
 - [home-assistant-polymer](https://github.com/home-assistant/home-assistant-polymer): Polymer UI.

For those new to contributing to open source software, make sure you are familiar with all of the tools and concepts used in Home Assistant before you start.

When contributing Home Assistant code:
 - [Github](https://guides.github.com/activities/hello-world/)
 - [Pip and Virtual Environments](https://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/)
 - [Python 3](https://www.python.org/)
 - [Pylint](https://www.pylint.org)
 - [Flake8](http://flake8.pycqa.org/en/latest/)
 - [Tox](http://tox.readthedocs.org/en/latest/)
 - [TravisCl](https://travis-ci.org/)

Home Assistant follows [Debian Stable](https://packages.debian.org/stable/python/python3) for the minimum Python version, which is currently [Python 3.5.3](https://www.python.org/downloads/release/python-353/).

When contributing 3rd Party code to be used by Home Assistant:
 - [Publishing your own PyPI package](https://jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/)
