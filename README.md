# COLOR GAME

![logo](./logo.png)

# DEMO


![demo](./demo.svg)

You can also watch demo on asciinema:
[https://asciinema.org/a/WrZEciKh3MjruYY8frLmi5Gjo](https://asciinema.org/a/WrZEciKh3MjruYY8frLmi5Gjo)

# How to run

### using Docker

```docker run -it $(docker build -q .)```

### running python locally

```poetry install```

```poetry run python color_game/main.py```

# Whats inside ?


Game is build using python and curses. nothing extra, except build in python modules (including curses).

Code is quite simple and it should be easy to follow,

`color_game/main.py` contain curces, main game loop and key handling

Also, there are vscode settings in this repo - so you should be able to debug code without any extra configuration (just choose proper venv)


I also add some simple tests (please don't get excited, I said simple)

![tests](./tests.png)


to run tests:

```poetry run pytest```

Yu can also use docker to run tests

or use vscode test explorer

# DEV TOOLS USED
- flake8
- pyright
- black
- pytest
- vscode



# DESCRIPTION

![logo](./description.png)

---

## Support

If this project saves you time, you can buy me a coffee:

[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor-mi4uu-ec4899?logo=github-sponsors&logoColor=white)](https://github.com/sponsors/mi4uu)
[![PayPal](https://img.shields.io/badge/PayPal-mi4uuuu-00457C?logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/mi4uuuu)

## License

AGPL-3.0-or-later, see [LICENSE](LICENSE).

Need it in a closed-source product, or can't meet the AGPL terms? Commercial licences are available on request: get in touch via [lipinski.work](https://lipinski.work).

By sending a pull request you agree that your contribution may be offered under both the AGPL and a commercial licence.

## Author

Made by [Michał Lipiński](https://lipinski.work) ([GitHub](https://github.com/mi4uu)).
