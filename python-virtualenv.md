# Python - Virtualenv

## Description
Virtualenv allows you to simply set up several, seperatly managed virtual Python environements. Every one of these virtual environements has it's own list of installed pip packages and it's even possible to assign a specific version of python to a virtualenv.

Virtualenv is perfect for solving dependency issues and making sure that your system's pip doesn't get uncomfortably full.

## Installation
On macOS: You can install virtualenv using [Pip](https://github.com/Opensource-Academy/package-managers/blob/master/python-pip.md):
```
pip install virtualenv
```
On Debian based Linux distributions: You can install virtualenv using [Apt](https://github.com/Opensource-Academy/package-managers/blob/master/apt.md) or Pip:
```
sudo apt install virtualenv
```
or
```
pip install virtualenv
```

## Configuration
Virtualenv configuration mainly happens when you use the 'virtualenv' command to set up a new virtualenv. See below for more information on how this works.

## Usage
To make use of virtualenv, first, a new virtualenv has to be set up. Once the initial setup is done, the environement has to be activated. Once activated, working from the virtualenv is like working with any regular system installed Python.

Set up a new environement.
```
virtualenv <name>
```
Set up a new environement with a specific Python version.
```
virtualenv -p python<version> <name> (e.g. virtualenv -p python3 env3)
```
Activate a virtualenv.
```
source <env name>/bin/activate (e.g. source env3/bin/activate)
```
Deactivate a virtualenv.
```
deactivate
```

```
   Copyright 2018 Opensource Academy

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
