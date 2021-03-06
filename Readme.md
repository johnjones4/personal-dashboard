# InBrief

[![Build Status](https://travis-ci.org/johnjones4/InBrief.svg?branch=master)](https://travis-ci.org/johnjones4/InBrief)[![Maintainability](https://api.codeclimate.com/v1/badges/28160129abdf4605c5fe/maintainability)](https://codeclimate.com/github/johnjones4/InBrief/maintainability)
[![NSP Status](https://nodesecurity.io/orgs/john-jones/projects/1cf328ae-6356-40fc-9c9f-4c8e2c5e4fd8/badge)](https://nodesecurity.io/orgs/john-jones/projects/1cf328ae-6356-40fc-9c9f-4c8e2c5e4fd8)

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

![App screenshot](screenshot.png)

## About

InBrief is a personal briefing app and dashboard powered by Electron and React. In one screen, InBrief provides an overview of your top RSS feeds, Twitter lists, local weather, email unread and flagged status, todos, and schedule. This app is meant to be the homepage and daily starting place for its users.

Each widget on the app's screen draws its data via various APIs, and InBrief is designed to support future widgets and APIs as is necessary or desired. The current supported services/APIs are:

* ICS calendar feeds
* Microsoft Exchange Web Services calendars
* Microsoft Exchange Web Services email
* IMAP email (including GMail)
* RSS/Atom
* Todoist
* Asana
* Twitter
* Weather Underground

## Installation

To install InBrief on your computer, head to the [Releases](https://github.com/johnjones4/InBrief/releases) section and download the appropriate file for your system. (Currently, there are only builds for Linux and Mac) Once running, there's a "plus" icon in the bottom right-hand corner of the window. Click that to add widgets. When a widget is added, click the edit button in its upper right-hand corner to configure it for your needs.

## Extending

To extend the capabilities of this application and add additional dashboard panels, see the [Development](Development.md) documentation
