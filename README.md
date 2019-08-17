# angular-8-ng-new

Angular 8 Starter App. Angular Cli command ```ng new``` is supposed to create a new seed app, but it gives you Angular 7.

This app has the bare minimum of files and configuration for an Angular 8 app.

This app upgrades the standard Angular Ng New app to the latest Angular 8.

Created by AngularExample. [https://github.com/angularexample](https://github.com/angularexample)

Full source code available at [https://github.com/angularexample/angular-8-minimal-app](https://github.com/angularexample/angular-8-minimal-app)

![angular-8-ng-new-screen-shot](https://github.com/angularexample/angular-8-ng-new/blob/master/src/assets/images/angular-8-ng-new-screen-shot.png)

## Table of Contents
- [About The Author](#about-the-author)
- [Project Setup](#project-setup)
  * [Prerequisites](#prerequisites)
  * [How To Install](#how-to-install)
  * [How To Run](#how-to-run)
- [Software Libraries Used](#software-libraries-used)
- [What Is Not Included](#what-is-not-included)
- [See My Other Angular Examples](#see-my-other-angular-examples)

## About The Author

**JC Lango** is a UI Architect and UI Developer for large scale web applications at several Fortune 500 companies.

He is an expert in **Angular**, **Polymer**, and **React** and maintains these sites at Github:

* **AngularExample** [https://github.com/angularexample](https://github.com/angularexample)
* **PolymerExample** [https://github.com/polymerexample](https://github.com/polymerexample)
* **ReactJSExample** [https://github.com/reactjsexample](https://github.com/reactjsexample)

JC may be available to work remote, and can be contacted at these links:
 
* LinkedIn: [https://www.linkedin.com/in/jclango](https://www.linkedin.com/in/jclango)
* Email: [jobs@jclango.com](mailto:jobs@jclango.com)

## Project Setup

### Prerequisites

You need to have Node and NPM installed on your PC.

[Downloading and installing Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

### How To Install

Download the source code using git or else download and unzip the zip file.

Open a terminal window and go to the project root folder.

You need to have npm installed globally.

Run `npm i` to install the required libraries.

### How To Run

Run `ng serve` for a dev server.

Navigate to `http://localhost:4200/`.

The browser will automatically reload if you change any of the source files.

## Software Libraries Used

The following software libraries are used:
```text
Angular 8.2.2
Angular Router
Angular Http
SCSS
```

Note: Angular Http is version 7, which is still the latest version, since version 8 has not yet been released.

The ```package.json``` is set to stay with all of the same minor versions, but many of the non-angular packages can actually be upgraded without breaking anything.
So feel free to try that.

## See My Other Angular Examples

In this same github you will see I have several other Angular Seed Apps.

Some of these have a more complete installation and configuration that are designed for a full scale project.


These other seed apps and examples also have the correct architecture for a large scale application.

Here are some of their included advantages:

* A much more complete set of installed library packages, intended for a large scale application.
* Configuration to allow things like lazy loading of modules.
* SCSS partials set up properly for global styles in a large scale app.
* Component selector prefix is set to "xxx" (can be renamed to your own prefix).
* Class names have a matching prefix, which is a best practice. 
* Tslint is set to validate the prefix.
* Shows you how to use a directory to contain all files for each component.
* Shows you how to include a shared common library module.

See one of the more complete examples to see how everything is set up:

[https://github.com/angularexample/angular-8-example-app](https://github.com/angularexample/angular-8-example-app)

---
