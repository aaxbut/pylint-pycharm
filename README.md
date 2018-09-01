# pylint-pycharm

[![Travis](https://img.shields.io/travis/leinardi/pylint-pycharm/master.svg?style=plastic)](https://travis-ci.org/leinardi/pylint-pycharm)
[![GitHub license](https://img.shields.io/github/license/leinardi/pylint-pycharm.svg?style=plastic)](https://github.com/leinardi/pylint-pycharm/blob/master/LICENSE) 
[![Waffle.io - Columns and their card count](https://badge.waffle.io/leinardi/pylint-pycharm.svg?columns=all&style=plastic)](https://waffle.io/leinardi/pylint-pycharm) 
[![Stars](https://img.shields.io/github/stars/leinardi/pylint-pycharm.svg?style=social&label=Stars)](https://github.com/leinardi/pylint-pycharm/stargazers) 

This plugin provides both real-time and on-demand scanning of Python files with Pylint from within PyCharm/IDEA.

Pylint is a Python source code analyzer which looks for programming errors,
helps enforcing a coding standard and sniffs for some code smells 
(as defined in Martin Fowler's Refactoring book).

![pylint plugin screenshot](https://github.com/leinardi/pylint-pycharm/blob/master/art/pylint-pycharm.png)

## Installation steps

The plugin requires [pylint](https://github.com/PyCQA/pylint) to be installed.

1. Download the latest [Pylint-x.x.x.zip](https://github.com/leinardi/pylint-pycharm/releases)
2. In PyCharm go to Settings... -> Plugins -> Install plugins from disc
   -> Select downloaded file -> Restart PyCharm when prompted.

## Configuration

The only configuration needed is to set the path to Pylint executable, and only if is not already
inside the PATH environment variable.

To reach the Plugin configuration screen you can go to Settings... -> Other Settings -> Pylint
or simply click the gear icon from the side bar of the Pylint tool window.

To change the path to your Pylint executable you can either type the path directly or use 
the Browse button to open a file selection dialog.

Once you changed the path you should press the Test button to check if the plugin is able to run
the executable.

![plugin settings screenshot](https://github.com/leinardi/pylint-pycharm/blob/master/art/pylint-settings.png)

### Inspection severity

By default, Pylint message severity is set to Warning. It is possible to change the severity level
by going to Settings... -> Editor -> Inspections -> Pylint -> Severity:

![plugin inspection severity screenshot](https://github.com/leinardi/pylint-pycharm/blob/master/art/pylint-inspection-severity.png)

## Usage

![plugin actions screenshot](https://github.com/leinardi/pylint-pycharm/blob/master/art/actions1.png)
![plugin actions screenshot](https://github.com/leinardi/pylint-pycharm/blob/master/art/actions2.png)

## Acknowledgements
_If I have seen further it is by standing on the sholders of Giants - Isaac Newton_

A huge thank you to the project [CheckStyle-IDEA](https://github.com/jshiell/checkstyle-idea), 
which code and architecture I have heavily used for when developing this plugin.

## License

```
Copyright 2018 Roberto Leinardi.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
```
