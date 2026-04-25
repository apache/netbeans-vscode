# Apache NetBeans Language Server for VS Code

Apache NetBeans Language Server for VS Code extension (VSNetBeans) is based on NetBeans IDE. Purpose of this project is to provide source code, build and integration of NetBeans IDE into VS Code.
See [Documentation](vscode/README.md) on VSNetBeans features.

## Requirements
* JDK 21 or higher to build and run Java LSP
* Node.js 20.18.1 or higher and npm installed to build VSIX

## Build
Apache NetBeans Language Server for VS Code consists of source code for VS Code integration in this repository and NetBeans IDE sources linked as [netbeans submodule](netbeans/) from main [NetBeans Git repo](https://github.com/apache/netbeans/).
* NetBeans IDE submodule is updated in `master` every week to link to latest commit ID in `master` in NetBeans IDE repository.
* Release branch of VSNetBeans is linked to release branch tag of NetBeans IDE.

See [BUILD.MD](BUILD.MD) how to build VSNetBeans using this repository and NetBeans IDE sources in submodule.

## Installation
In VS Code IDE Extensions panel search for *NetBeans*, select **Language Server for Java by Apache** and Install.

## Reporting Issues
Issues for VSNetBeans has to be filled in this repository Issues section on GitHub.
