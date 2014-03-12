slackpkg-templates
==================

# Motivation

Slackware is great! Vanilla philosophy always wins.
using slackpkg templates features to manage dependencies could save a lot of time when installing software.

# Installation

Run this command as *root*

```bash
$ git clone https://github.com/fibo/slackpkg-templates /etc/slackpkg/templates/
```

# Usage

A *foo.template* file contains a list of all packages needed to install software *foo* in alphabetic order.

To install software *foo* use `slackpkg` as usual

```bash
$ slackpkg install-template foo
```

