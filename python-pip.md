# Package managers - Pip (Python)

## Description
Pip is a package manager for Python; you can use it to download and install packages (basically; Python scripts written by others) which can be imported into your own Python scripts.

## Installation
On MacOS: if you don't have pip yet, you can use Homebrew or simply use the Python installer from the official Python website: this version of Python comes with Pip included.

On Debian based Linux distributions: run the following command to install pip:
```
apt install python3-pip
```

## Configuration
Pip should not require any further configuration. Simply run a pip install <package> to install a package.

> Note: It's probably smart to use Pip together with Python's Virtualenv.

## Usage
Install a package.
```
pip install <package>
```
Install packages from a 'requirements.txt' file.
```
pip install -r requirements.txt
```
Show list of installed packages
```
pip list
```

## Test

How do you remove a package?

How do you easily create a requirements.txt file?

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
