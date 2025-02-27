# pymake
Production grade makefile for Python Poetry projects.


## Requirements

- GNU make 3.81 (Tested with 3.81)
- Python 3.10 or higher (Tested with 3.10)
- Poetry project management tool

# How to setup poetry and Makefile

## 1
```shell
poetry new --src my-project
```

## 2
copy the Makefile in the newly created `my-project` dir

## 3 - Install dependencies

```shell
poetry add mypy isort

```

# Makefile Usage

## Installation

To install the project dependencies, run:

```sh
make install
```

## Building the Project
To clean, lint, format, sort, test, and build the project, run:

```sh
make build
```

## Running Tests
To run all tests using pytest, run:

```sh
make test
```

## Linting the Project
To lint the project using mypy, run:

```sh
make lint
``` 

## Formatting the Project
To format the project using black, run:

```sh
make format
``` 

## Sorting imports
To sort imports using isort, run:

```sh   
make sort
``` 

## Cleaning the Project
To clean the project, run:

```sh   
make clean
``` 

## Help
To see all available commands, run:

```sh   
make help
```