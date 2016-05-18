# [Application Title]
**[INSERT concise single paragraph that describes your product in modest, non-lofty terms.]**

_"Angular is a development platform for building mobile and desktop web applications."_

_"HTTPie (pronounced aitch-tee-tee-pie) is a command line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. It provides a simple http command that allows for sending arbitrary HTTP requests using a simple and natural syntax, and displays colorized output. HTTPie can be used for testing, debugging, and generally interacting with HTTP servers."_

--------------------
**[INSERT links to your coverage images here]**
[![Build Status](https://secure.travis-ci.org/gotwarlost/istanbul.png)](http://travis-ci.org/gotwarlost/istanbul) [![Dependency Status](https://gemnasium.com/gotwarlost/istanbul.png)](https://gemnasium.com/gotwarlost/istanbul)
--------------------

**[INSERT a link to your deployed version]**

## Table of Contents 
* [Features](#features)
* [Getting started and configuration](#getting-started)
* [The command line](#the-command-line)
* [Ignoring code for coverage](#ignoring-code-for-coverage)
* [API](#api)
* [Changelog](https://github.com/gotwarlost/istanbul/blob/master/CHANGELOG.md)
* [License and credits](#license)

## Example / Usage
**[INSERT a description of how to use your product, if applicable]**
* Do you have an outward-facing API? If so, make sure API documentation is linked in TOC or here.
* Does your product have any command-line inputs?

**[INSERT awesome GIF of your project]**
http://gifmaker.me/

## Getting Started and Configuration
_Use this section to describe the spin-up process. Installation steps, dependencies, etc._
* Pretend your reader has never worked with your specific frameworks or languages. 
* Do you have multiple environments? (dev, staging, etc.)?
* What is your testing workflow?

Please install Python/Flask dependencies within the root directory
```
$ virtualenv .
$ source bin/activate
$ pip install -r requirements.txt
```

Next, install the client-side dependencies
```
$ sudo npm install -g bower
$ bower install
```
**For testing**
```
$ npm install
```

You're good to go. Start the server with:
```
$ npm start
```

## Architecture
### High Level Architecture
![](http://i64.tinypic.com/2zpp661.png)
### Database Schema
Postgres using SQLAlchemy ORM
![](http://i68.tinypic.com/23i6plz.jpg)

## API Documentation
##### Public End Points
|Description|Endpoint|
|---|---|
|[Log-in OAuth](#get-receive_code)|GET /receive_code/|
|[Log-in Demo](#post-demo)|POST /demo/|
|[Log-out current user](#post-logout)|POST /logout|
|[Get User Info](#get-userbasicinfo)|GET /user/basicinfo/|
|[Get User Relatives](#post-userrelativesinfo)|POST /user/relativesinfo/|
|[Get User's SNP Data](#post-usersnpinfo)|POST /user/snpinfo/|

##### Admin Only
|Description|Endpoint|
|---|---|
|[Access to 23&Me Individual data](#get-1useruserid)|GET /1/user/:userID|
|[Access to 23&Me Genotype data](#get-1genotypeuserid)|GET /1/genotype/:userID|
|[Access to 23&Me Relative data](#get-1relativesuserid)|GET /1/relatives/:userID|

## Contributing
**[INSERT contributing workflow steps or link here]**
[INSERT APP NAME] was built using waffle.io as the project organization tool.
Please visit [here](gitflow.md) for our workflow guidelines.

## Questions and Issues
For any issues, please refer to [**our issues page**](https://github.com/[INSERT TEAM]/[INSERT REPO]/issues)
Please direct any questions regarding [INSERT APP NAME] to [**our wiki page**](https://github.com/[INSERT TEAM]/[INSERT REPO]/wiki)

## Meta
Links to Contributors (your github profiles and roles)
"Distributed under the MIT License."







