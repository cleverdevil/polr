# [![Logo](http://i.imgur.com/aOtrJNz.png)](https://project.polr.me)

:aerial_tramway: A modern, minimalist, and lightweight URL shortener.

[![GitHub license](https://img.shields.io/badge/license-GPLv2%2B-blue.svg)]() 
[![Builds status](https://travis-ci.org/cydrobolt/polr.svg)](https://travis-ci.org/cydrobolt/polr) 
[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](http://polr.readthedocs.org/en/latest/)

Polr is an open-source link shortening web application designed to operate at a brisk pace while offering a full-featured experience. It allows you to host your own URL shortener, to brand your URLs, and to gain control over your data. Polr is especially easy to use, and provides a modern, themable feel.

[Getting Started](http://docs.polr.me/en/latest/user-guide/installation/) - [API Documentation](http://docs.polr.me/en/latest/developer-guide/api/) - [Contributing](https://github.com/cydrobolt/polr/blob/master/CONTRIBUTING.md) - [Bugs](https://github.com/cydrobolt/polr/issues) - [IRC](http://webchat.freenode.net/?channels=#polr)

### Upgrading from 1.x

**Please do not attempt to upgrade directly to 2.x.**

Polr 1.x currently cannot be upgraded to 2.x automatically. There are breaking changes in the API, configuration files, and database structure. A migration will be provided once 2.0 stable is officially released. In the meantime, it is okay to upgrade between different versions in the 1.x arch, which do not have breaking changes.


#### Quickstart

Polr is written in PHP and Laravel, using MySQL as its primary database.

 - To get started with Polr on your server, check out the [installation guide](http://docs.polr.me/en/latest/user-guide/installation/). You can clone this repository, or download a [release](https://github.com/cydrobolt/polr/releases). 
 - To get started with the Polr API, check out the [API guide](http://docs.polr.me/en/latest/developer-guide/api/).


_Installation TL;DR: clone or download this repository, set document root to `public/`, MySQL create database, go to `yoursite.com/setup`_

#### Demo

Polr operates a demo instance at [demo.polr.me](http://demo.polr.me). You can use the demo instance to develop your API implementation, try out the admin panel, or simply experience the app without needing to install it on your own servers. The demo instance may be periodically reset, so please do not use the demo as a production URL shortener.

Admin username: demo-admin (password is same as username)

Normal user username: demo-user (password is same as username)


####Versioning

Polr uses [Semantic Versioning](http://semver.org/)


####License


    Copyright (C) 2013-2016 Chaoyi Zha

    This program is free software; you can redistribute it and/or
    modify it under the terms of the GNU General Public License
    as published by the Free Software Foundation; either version 2
    of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
