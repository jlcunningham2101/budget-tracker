# Budget Tracker

## Table of Contents

- [Description](#description)
- [Features](#features)
- [User-Story](#user-story)
- [Acceptance-Criteria](#acceptance-criteria)
- [Usage](#usage)
- [Webpage-Screenshots](#webpage-screenshots)
- [Github-Link](#github-link)
- [Deployed-Link](#deployed-link)
- [Contributor](#contributor)

### Description

This application allows users to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online.

### Features

This application includes the following features:

- Express.js
- IndexedDB
- MongoDB

### User Story

AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

### Acceptance Criteria

GIVEN a CMS-style blog site

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

### Usage

Application users will need to use IndexedDB to add offline functionality and PWA to add a service worker to your application. The budget tracker has a server and uses MongoDB as its database, so you’ll need to deploy this application to Heroku using MongoDB Atlas

### Webpage Screenshots

### GitHub Link

https://github.com/jlcunningham2101/budget-tracker

### Heroku Link

### Contributor

Name: Jill Cunningham
Email: jleighcunningham@gmail.com
GitHub URL: https://github.com/jlcunningham2101
