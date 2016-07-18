# configure-c-compiling README

This extension was created to automate the creation of the launch.json, tasks.json files and a simple makefile for c projects.

## Features

Generates a the launch.json that enables VSCode to launch a C application and generates a task in tasks.json that compiles the source code.

This extension has only one command: Generate Configurations and it overwrites the 3 files.

## Requirements

You need MinGW or other fork in Windows and the C/C++ extension for VSCode.

## Extension Settings

This extension contributes the following settings:

* `configure-c-compiling.mingwPath`: Sets the full path to MinGW folder in Windows

## Release Notes

### 0.1.1
    Correction of task command in Linux

### 0.1.0
    Initial Release
