# ansible-domoticz

[![Build Status](https://travis-ci.com/chubchubsancho/ansible-domoticz.svg?branch=master)](https://travis-ci.com/chubchubsancho/ansible-domoticz)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?logo=github&style=flat)](https://raw.githubusercontent.com/chubchubsancho/ansible-domoticz/master/LICENSE)

1. [Overview](#overview)
1. [Description](#role-description)
1. [Setup](#setup)
1. [Usage](#usage)
1. [Limitations](#limitations)
1. [Development](#development)
1. [Miscellaneous](#miscellaneous)

## Overview

## Description

This role install all prerequisites to Domoticz installation and finaly deploy it on system.
You ca as well install stable release, beta release and copile Domoticz from source.

Role is under development so feature will be add as they have been developped.

## Setup

Copy this role in your roles folder without *ansible-* in the name.

## Usage

* install domoticz stable release

```yaml
---
# The user which the Domoticz daemon run as
domoticz_user: "domoticz"

# The group which the Domoticz daemon run as
domoticz_group: "domoticz"

# The directory where the downloaded files will be placed
domoticz_download_dir: "/home/domoticz"

# The name of the untarred Domoticz directory
domoticz_install_dir: "domoticz"

# The domoticz port
domoticz_port: 8080

# Use SSL for domoticz
domoticz_https: false
domoticz_https_port: 8081

# install Domoticz beta
domoticz_beta: false

# compile domoticz from source
domoticz_source: false
```

## Limitations

## Development

## Miscellaneous
