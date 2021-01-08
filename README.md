# Final Project: Python System Automation Tool

## Project Proposal:

Create a Python application that removes manual intervention of simple tasks and system queries. The tool will help a user use an application to choose if they want to copy, move, delete, rename, files or folders. They will also be able to get information about the system, what files are contained inside a folder, and retrieve file/folder size information from one console.

Example:
 - Copy/Rename/Delete/Move files and folders
 - Retrieve # of files in a specified location
 - Retrieve info of current running tasks
 - Retrieve info of folder/file size
 - ...

## Classes

Classes are designed to get/set src_path & dest_path to be used as private variables for internal class usage with no need for parameters in method calls

Files Class - This class will contain actions related to files. Get/Set private methods will be used to set file paths.

class Files:
    
    def _init__():

    # Copy file(s)
    def copy(self):
        pass

    # Move file(s)
    def move(self):
        pass
    
    # Remove file(s)
    def remove(self):
        pass

    # Delete file(s)
    def delete(self):
        pass


Folder Class - This class will contain actions related to folders. Get/Set private methods will be used to set folder paths.

class Folders:
    
    def _init__(self):
        pass

    # Copy folder(s)
    def copy(self):
        pass

    # Move folder(s)
    def move(self):
        pass
    
    # Remove folder(S)
    def remove(self):
        pass

    # Delete folder(s)
    def delete(self):
        pass

System_Tasks Class - This class will contain actions related to retrieving information from the system.

class System_Tasks:

    def __init__(self):
        pass 
    
    def system_info(self):
        pass

    def find_files_ext(self):
        # find files that contains extension (i.e. .zip, .pdf. .png, .txt etc)
        pass

    def find_files_contains(self):
        # find files that contain 'string'
        pass

    def folder_info(self):
        # get list of files in folder and folder sizae
        pass

    def file_size(self):
        pass

## Libraries/Modules
Python Libraries/Modules to be used as part of the project are below:
```
import os
from os import listdir
import subprocess
import shutil
import easygui
import tkinter as tk
from tkinter import filedialog
from tkinter import *
from tkinter import simpledialog
from distutils.dir_util import copy_tree
from fnmatch import fnmatch
import psutil
import platform
from datetime import datetime
import time
from columnar import columnar
import sys
```