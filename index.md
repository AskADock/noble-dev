## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Links](#links)
* [Team](#team)
* [Community Feedback](#community-feedback)

## Overview

Our platform, Noble, is in collaboration with the Hawaii Air National Guard 154 Medical Group to allow efficiency and comfortability in finding medical processes. Service members will be able to ask medically related questions anonymously and navigate through the application to find frequenty asked questions. This application will illustrate various technologies useful to  software engineering, including: 

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://react.dev/) for component-based UI implementation and routing.
* [React](https://react-bootstrap.github.io/) Bootstrap CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## Deployment
View our website application here: Noble

## Activity Badges
[![ci-ask-a-doc](https://github.com/ics-software-engineering/meteor-application-template-production/actions/workflows/ci.yml/badge.svg)](https://github.com/ics-software-engineering/meteor-application-template-production/actions/workflows/ci.yml)

## User Guide
This section provides a walkthrough of the Noble user interface and its capabilities.

### Landing Page
The landing page is presented to users when they visit the top-level URL to the site. It provides our motto and some previews of our application.

*We are still in the initial stages of developing this application. We intend to enhance the UI design over the course of our project.*

## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation
First, [Install Meteor](https://docs.meteor.com/install.html).

Second, visit the [Ask A Doc application github page](https://github.com/AskADock/ask-a-doc.github.io), and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer ("clone" the file to your computer!).

Third, cd into the bowfolios/app directory and install libraries with:
```angular2html
$ meteor npm install
```

Fourth, run the system with:
```angular2html
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Application Design
Noble is based upon [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/) and [meteor-example-form-react](https://ics-software-engineering.github.io/meteor-example-form-react/).  Please use the videos and documentation at those sites to better acquaint yourself with the basic application design and form processing in Kalo Stems.

## Continuous Integration
Noble uses [Github Actions](https://docs.github.com/en/free-pro-team@latest/actions) to automatically run ESLint and TestCafe each time a commit is made to the default branch.

## Team
Noble of Ask A Doc is designed and implemented by Lauren Clayton, Rina Ogino, Thomas Rivera, Ryne Stagen, and Brandon Underwood.

## Community Feedback
We are interested in your experience using Noble! Please take a couple of minutes to fill out the Noble Feedback Form.
