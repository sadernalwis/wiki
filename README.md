<div align="center">

<img src="https://static.requarks.io/logo/wikijs-full.svg" alt="Wiki.js" width="600" />

[![Release](https://img.shields.io/github/release/Requarks/wiki.svg?style=flat&maxAge=3600)](https://github.com/Requarks/wiki/releases)
[![License](https://img.shields.io/badge/license-AGPLv3-blue.svg?style=flat)](https://github.com/requarks/wiki/blob/master/LICENSE)
[![Backers on Open Collective](https://opencollective.com/wikijs/all/badge.svg)](https://opencollective.com/wikijs)
[![Downloads](https://img.shields.io/github/downloads/Requarks/wiki/total.svg?style=flat)](https://github.com/Requarks/wiki/releases)
[![Docker Pulls](https://img.shields.io/docker/pulls/requarks/wiki.svg)](https://hub.docker.com/r/requarks/wiki/)  
[![Build status](https://dev.azure.com/requarks/wiki/_apis/build/status/build)](https://dev.azure.com/requarks/wiki/_build/latest?definitionId=9)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=wiki&metric=alert_status)](https://sonarcloud.io/dashboard?id=wiki)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=wiki&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=wiki)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=wiki&metric=security_rating)](https://sonarcloud.io/dashboard?id=wiki)
[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)  
[![Chat on Slack](https://img.shields.io/badge/slack-requarks-CC2B5E.svg?style=flat&logo=slack)](https://wiki.requarks.io/slack)
[![Twitter Follow](https://img.shields.io/badge/follow-%40requarks-blue.svg?style=flat&logo=twitter)](https://twitter.com/requarks)
[![Subscribe to Newsletter](https://img.shields.io/badge/newsletter-subscribe-yellow.svg?style=flat&logo=mailchimp)](https://wiki.js.org/newsletter)

##### A modern, lightweight and powerful wiki app built on NodeJS

</div>

- **[Official Website](https://wiki.js.org/)**
- **[Documentation](https://docs.requarks.io/)**
- [Requirements](https://docs.requarks.io/install/requirements)
- [Demo](#demo)
- [Change Log](https://docs.requarks.io/releases)
- [Feature Requests](https://wiki.js.org/feedback)
- [Chat with us on Slack](#slack)
- [Translations](#translations) *(We need your help!)*
- [Special Thanks](#special-thanks)
- [Contribute](#contributors)

<h2 align="center">Donate</h2>

<div align="center">

Wiki.js is an open source project that has been made possible due to the generous contributions by community [backers](https://wiki.js.org/about). If you are interested in supporting this project, please consider [becoming a sponsor](https://github.com/users/NGPixel/sponsorship), [becoming a patron](https://www.patreon.com/requarks), donating to our [OpenCollective](https://opencollective.com/wikijs), via [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FLV5X255Z9CJU&source=url) or via Ethereum (`0xe1d55c19ae86f6bcbfb17e7f06ace96bdbb22cb5`).
  
This project exists thanks to all the people who contribute. [[Contribute]](https://github.com/Requarks/wiki/blob/master/.github/CONTRIBUTING.md).
<a href="https://github.com/Requarks/wiki/graphs/contributors"><img src="https://opencollective.com/wikijs/contributors.svg?width=890" /></a>



    sudo apt update
    sudo apt install postgresql postgresql-contrib

sudo -i -u postgres

SHOW hba_file;


psql -t -P format=unaligned -c 'show hba_file';

https://gist.github.com/AtulKsol/4470d377b448e56468baef85af7fd614


postgres=#CREATE ROLE wikijs WITH SUPERUSER CREATEDB CREATEROLE LOGIN ENCRYPTED PASSWORD 'wikijsrocks';

sudo service postgresql restart
//
user#  sudo su postgres
postgres#  pg_ctl reload

If it complains about not having a data directory, you'll have to do it from within PostgreSQL itself.

psql -U postgres
postgres=> SELECT pg_reload_conf();

psql -d postgres -U wikijs

create database wiki;


To get information about current connection from psql comman prompt:

\conninfo

This display more informations, though.

To change user:

\c - a_new_user

The ‘-’ is substitute for current database. You can write this to change database and user:

\c a_new_database a_new_user

Using SQL to get information:

SELECT current_user;
