# CI/CD Tools and Practices Final Project Template

## Project Name: ci-cd-final-project

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

## Setup

After entering the project, you need to run the following command to set up the project:

```bash
bash bin/setup.sh
```

Then you need to exit the terminal and open a new terminal to continue.

## Running the Tests

As a sanity check, you can run the tests with the following command:

```bash
nosetests
```

## What's featured in the project?

The project features a RESTful API that allows users to manage and track counters, including:

* `service/routes.py` -- the main Service routes using Python Flask
* `service/common` -- common log and error handlers
* `tests/test_routes.py` -- test cases for the microservice
