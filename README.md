# pterobot

![lint-and-test]
[![Latest version][pypi-img]][pypi]
[![Discord][discord-img]][discord-join]

PteroBot is a Discord bot that can be used to view and control your 
Pterodactyl game servers.

PteroBot also has a hosted version in addition to the open source 
self-hosted version.  To join PteroBot to your server immediately navigate 
to https://join.pterobot.net.

## Getting Started

There are a few easy ways to get started using PteroBot.

### Install from pip

Install from pip by running `pip install pterobot`

### Using Docker

Get the Docker image from `ghcr.io/iamkubi/pterobot`

### Using Pterodactyl

Get the Pterodactyl egg from `https://github.com/iamkubi/eggs/pterobot`

## Dependencies

Keen observers may notice a dependency on pydactyl which does not support 
async usage.  Fear not, as part of the pterobot development I am also adding 
an async client to pydactyl.

[pulls]: https://github.com/iamkubi/pterobot/pulls

[issues]: https://github.com/iamkubi/pterobot/issues

[pypi]: https://pypi.python.org/pypi/pterobot/

[pypi-img]: https://img.shields.io/pypi/v/pterobot.svg

[codecov]: https://codecov.io/gh/iamkubi/pterobot

[codecov-img]: https://codecov.io/gh/iamkubi/pterobot/branch/main/graph/badge.svg

[discord-img]: https://img.shields.io/badge/discord-join-7289DA.svg?logo=discord&longCache=true&style=flat

[discord-join]: https://discord.gg/djtpCkScPz

[lint-and-test]: https://github.com/iamkubi/pterobot/actions/workflows/lint-and-test.yml/badge.svg?branch=main (https://github.com/iamkubi/pterobot/actions/workflows/lint-and-test.yml)