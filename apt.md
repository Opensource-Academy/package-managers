# Package managers - Apt

## Description
Apt is the default package manager for Debian based linux distributions. Noteworthy examples include: Ubuntu or Raspbian.

> Note: apt recently replaced 'apt-get', but in most forums and manuals you will still see 'apt-get install', you can just ignore the '-get' part on Debian based systems that run a relatively new version of their distro. If apt does not work, fall back to 'apt-get'.

> Note: apt is only available on Debian based Linux distributions, other distributions usualy come with their own package manager. By learning apt, it will be much easier to lean how to work with other package managers.

> Note: if you are on MacOS, you will use a different package manager called Homebrew, which is also described in these docs.

## Configuration
Apt should be configured out of the box.

## Usage
Remember to run apt with 'sudo'.

Install a package.
```
apt install <package>
```
Remove a package
```
apt remove <package>
```
Remove a package and all it's dependencies.
```
apt purge <package>
```
Update package list
```
apt update
```
Upgrade packages
```
apt upgrade
```

## Test
If you are on Ubuntu (or something similar like Xubuntu) or Raspbian try to install the program `git` with apt.

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
