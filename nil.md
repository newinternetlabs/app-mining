# New Internet Labs App Review Policies and Procedures

[New Internet Labs](https://newinternetlabs.com) (NIL) is the digital rights reviewer in the Blockstack ecosystem. This document outlines our review policies and procedures.

## Scope of review

Apps are currently reviewed for use of Blockstack's Gaia storage technology and use of Blockstack Auth. 

## Eligible platforms & environments

We are able to review native apps on the following platforms:

* Windows
* macOS
* Ubuntu Linux
* Android
* iOS

Desktop operating systems are the most recent public release and are generally running in virtual machines. iOS review is conducted on an iPhone currently supported by Apple in the latest public non-beta release of iOS. Android review is conducted on a Pixel 2 or equivalent hardware with the most recent updates provided by the manufacturer.

Web apps are reviewed on the most recent stable releases of one of the four major browsers: Firefox, Chrome, Safari or Edge. Desktop browsers are used.

### Selecting review platform

We select one desktop operating system, mobile operating system and web  browser at the beginning of each month's review. 

#### Web apps

All web apps are reviewed on the same browser/desktop operating system combination.  Web apps that prevent that use of a particular browser/os combination or do not function on a given combination are marked as ineligible.

#### Non-web apps 

When apps are available in native or mobile in addition to web versions, the web version is reviewed. If native apps are available on multiple platforms, apps are only reviewed on the chosen platform for the given month. If the native app is unavailable on the chosen review platform it will be reviewed on the platform on which it is available.

## Scoring

Points are awarded from -1 to 4 for Blockstack Auth and -1 to 1 for Gaia Storage. The maximum total score is 5 points.

### Blockstack Auth
Apps must use Blockstack Auth to be eligible for app mining. If an app does not use Blockstack Auth, it is marked as ineligible, which disqualifies it from App Mining for this month.

If an app attempts to use Blockstack Auth but the reviewer cannot successfully sign in or an error occurs during the process, the app receives a score of -1.

If an app successfully implements Blockstack Auth and Blockstack Auth is the only form of authentication or user sign in mechanism, the app receives 4 points.

Apps that offer Blockstack as one of multiple authentication methods will receive 1 to 3 points based on the placement of Blockstack Auth in relationship to other methods. 

Apps that use Blockstack Auth as the primary authentication 3 points. 

Apps that use Blockstack Auth as one a number of authentication methods, all with equal placement will receive 2 points.

Apps that use Blockstack Auth as  secondary authentication method will receive 1 point.

Primary vs secondary is largely a subjective judgement made by the app reviewer taking into account the placement of the Sign in with Blockstack button in the app in relation to other authentication methods. Please see [these drawings](DigitalRightsAuthScoringCriteria.pdf) for guidance.

### Gaia Storage

Apps that do write to Gaia storage receive 0 points.

Apps that write to Gaia storage without any errors receive 1 point.

Apps that have errors when writing to Gaia storage receive -1 points.

##  Review Procedure
Apps for a given month are divided among multiple reviewers. Each app is reviewed a minimum of once. If a reviewer has trouble reviewing an app the reviewer marks the app as "needs re-review" and the app is reviewed a second time by the lead app reviewer. Any app that is is awarded less than a total of 5 points is also reviewed a second time by the lead reviewer. 

In the event NIL encounters a problem with an app during review, we typically take screenshots or a short video of the screen to demonstrate the problem. The reviewer also makes a note in the notes section of the app review spreadsheet of the problem. These are provided to PBC along with app scores.

With respect to usage of Gaia, if after two reviews, neither reviewer is able to find usage of Gaia (ie. because such usage is an insignificant or non-obvious part of the app), the app is awarded a Gaia score of zero.

## Communications

App developers are expected to have their apps ready by the beginning of the App Mining period. We don't communicate in advance on which days we will conduct the review. Communication about app mining should be conducted via the Blockstack PBC app mining team. They should be included on any communications with NIL by cc'ing the email address mining@app.co.
