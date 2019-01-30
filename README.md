# Vaporify

Simple starter kit for web applications in Swift and Vapor!

* Version: v0.0.1

## Table of Contents

* [Quick Start](#quick-start)
* [Build for production](#build-&-run)
* [Deployment](#deployment)
* [Resources](#resources)
* [Troubleshooting](#troubleshooting)
* [Vapor Style Guide](#vapor-style-guide)

## Quick start

* Clone the repo.
* Run `vapor build` and `vapor run`.

## Build & Run

You can use the toolbox to build and run your Vapor app.

```bash
vapor build
vapor run
```

We recommend building and running through Xcode if you have a Mac. It's a bit faster and you can set breakpoints! Just use `vapor xcode` to generate an Xcode project.

## Deployment

Deploying your project to Vapor Cloud is simple, it's built right into the Vapor Toolbox. Just run this command from within the root directory of your project.

```bash
vapor cloud deploy
```

For a detailed guide, visit [Vapor Cloud → Quick Start.](https://docs.vapor.cloud/quick-start/)

## Resources

* [Vaporschool](https://github.com/vaporberlin/vaporschool)

## Troubleshooting

If you are experiencing problems with SPM, sometimes cleaning your project can help.

```bash
vapor clean
```

## Vapor Style Guide

Vapor Style Guide is available [here.](https://docs.vapor.codes/3.0/extras/style-guide/)