# Beggar [![Build Status](https://secure.travis-ci.org/bkzl/beggar.png)](http://travis-ci.org/bkzl/beggar)

## Description

Beggar is a tool for generating time reports from your Basecamp account

Example output:

    78% || 140.0h, -12.0h || 5320.0 zł, -456.0 zł

where

    78% - working days progress in current month
    140.0h, -12.0h - worked hours ratio
    5320.0 zł, -456.0 zł - salary ratio

### Installation

Install it like any ruby gem

    gem install beggar

and run by

    beggar

### Configuration

Before first use, beggar will try to create configuration file in your home directory (~/.beggar)

Example config:

    company: pear
    token: abc123
    rate: 50.0

## Changelog
  v1.0.0 - first stable release

