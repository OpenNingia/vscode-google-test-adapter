# This extension is now superseded by [VSCode Catch2 Test Adapter](https://github.com/matepek/vscode-catch2-test-adapter)

# Google Test Explorer

This extension allows you to run your [Google tests](https://github.com/google/googletest) using the 
[Test Explorer for VS Code](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer).

[![Build Status](https://travis-ci.com/OpenNingia/vscode-google-test-adapter.svg?branch=master)](https://travis-ci.com/OpenNingia/vscode-google-test-adapter)

## Configuration

* `gtestExplorer.executable`: The relative path describing the location of your test executable (relative to the workspace folder)
* `gtestExplorer.env`: Environment variables to be set when running the tests
* `gtestExplorer.cwd`: The working directory where Google is run (relative to the workspace folder)
