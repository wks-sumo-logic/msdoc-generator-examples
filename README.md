
MS Document Generator - A way to build MS documents
===================================================

This is a project to handle examples of how to build MS Excel and Powerpoint files

* Examples for MS Excel files ( including graphs ) 

* Examples for MS Powerpoint files

Installing the Scripts
=======================

All scripts are designed to be used within a batch script or DevOPs tool such as Chef or Ansible.

Written in python3, all scripts are listed below, and there is a Pipfile to show what modules are required to run.

You will need to use Python 3.6 or higher and the modules listed in the dependency section.  

Please follow the following steps to install:

    1. Download and install python 3.6 or higher from python.org. Append python3 to the LIB and PATH env.

    2. Download and install git for your platform if you don't already have it installed.
       It can be downloaded from https://git-scm.com/downloads
    
    3. Open a new shell/command prompt. It must be new since only a new shell will include the new python 
       path that was created in step 1. Cd to the folder where you want to install the scripts.
    
    4. Execute the following command to install pipenv, which will manage all of the library dependencies:
    
        sudo -H pip3 install pipenv 

    5. Clone this repository. This will create a new folder 

    6. Change into the this new folder. Type the following to install all the package dependencies 
       (this may take a while as this will download all of the libraries that it uses):

        pipenv install
        
Dependencies
============

See the contents of "pipfile"

Script Names and Purposes
=========================

To Do List:
===========

* Ensure we have samples for specific goals in addition to sample monolithic scripts

License
=======

Copyright 2021 Wayne Kirk Schmidt

Licensed under the GNU GPL License (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    license-name   GNU GPL
    license-url    http://www.gnu.org/licenses/gpl.html

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Support
=======

Feel free to e-mail me with issues to: wschmidt@sumologic.com or wayne.kirk.schmidt@gmail.com
I will provide "best effort" fixes and extend the scripts.

