# README

This repository contains a Ruby on Rails scaffold that can be used with [Visual Studio Code Dev Containers](https://code.visualstudio.com/docs/devcontainers/containers).

## Stack

|               | Version        |
|---------------|----------------|
| Ruby          | 3.2.2          |
| Ruby on Rails | ~> 7.0.5       |
| Postgres      | latest (13.11) |

## Installation

### Without Dev Containers

To install without using Dev Containers, follow these steps:

1. Install dependencies by running the command `$ bundle install` or `$ bundle`.
2. Set up the database by running `$ rails db:setup`.

### With Dev Containers

#### Presiquisites

Before using Dev Containers, ensure that you have the following installed:

- [Visual Studio Code](https://code.visualstudio.com/)
- Docker
- Dev Containers extension

Please refer to the following documents for system requirements and installation instructions:

- [System requirements](https://code.visualstudio.com/docs/devcontainers/containers#_system-requirements)
- [Installation](https://code.visualstudio.com/docs/devcontainers/containers#_installation)

#### Reopen the project in Container

To open the project in a Dev Container, follow these steps:

1. Press <kbd>F1</kbd> or <kbd>Cmd + Shift + P</kbd> to open the Command Palette.
2. Type `Dev Containers` in the search bar to see the full list of commands.
3. Select `Dev Containers: Reopen in Containers` from the suggestions list.

Waiting for containers to be ready and all set.

## Running the project

If necessary, update the `database` configurations in `database.yml`. You may need to re-execute the command `$ rails db:setup`.

To start the server, run the command `$ rails server` or `$ rails s` in your terminal.

> Note: If you're running the project in a dev container, make sure to access the container before executing the `$ rails s` command or open the VSCode terminal.

You can now visit http://localhost:3000/ to see the project running.
