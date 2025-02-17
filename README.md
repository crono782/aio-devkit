## Overview

This is a self-hosted all-in-one development environment that allows you to reproduce services commonly offered by large providers like GitHub. The aim is to maintain control over personal and client data while providing an effective, cost-free setup for your development needs.

This project is designed to be portable, allowing you to easily spin up or down services as necessary, making it perfect for side projects and remote development.

You can watch the complete setup process on [YouTube](https://www.youtube.com/watch?v=lR_Q3uwdcAE&list=PLIS2XlWhBbX_wz_BsD-TYrZEUrUVCm1IO&index=1).

## Key Features

1. **Source Code Management**: Utilize [Gitea](https://github.com/go-gitea/gitea) to manage your source code effectively. Gitea also acts as the single sign-on authentication provider for other services. 
1. **CI/CD Pipeline**: Set up continuous integration and deployment pipelines using [Gitea Actions](https://docs.gitea.com/next/usage/actions/overview/).
1. **Remote Development**: Spin up remote development environments using [Coder](https://github.com/coder/coder), which provides a web-based version of Visual Studio Code, complete with support for extensions.
1. **Recreate GitHub Gists**: Use [OpenGist](https://opengist.io/) to mirror the functionality of GitHub Gists for note-taking and scratch pads.
1. **Hosted Static Websites**: Recreate GitHub Pages capabilities with [Codeberg](https://codeberg.org/).
1. **Static Code Analysis**: Integrate [SonarQube](https://www.sonarsource.com/products/sonarqube/) for static code analysis to ensure code quality.
1. **Dependency Management**: Automate dependency updates using [Renovate](https://docs.renovatebot.com/), which inspects repositories and ensures up-to-date dependencies.
1. **Caching and Registry**: Utilize [ProxPi](https://github.com/EpicWink/proxpi) for PyPI package caching and set up a local Docker [registry](https://hub.docker.com/_/registry) to avoid rate limits from Docker Hub.

## Development Environment

The entire setup can be hosted on an old Intel NUC unit or even your laptop/desktop, enabling low-resource utilization while providing a full suite of utilities for software development. The modular nature allows for easy customization and control over the services you want to enable or disable at any given time.

## Getting Started

This project will guide you through the process of building your own "GitHub in a Box" from scratch, outlining the steps and configurations required for each component.

## Prerequisites
- Access to a suitable machine with at least 8 GB of RAM
- A Linux distribution, such as Ubuntu
- Docker and Docker Compose
