# CogSvcsSamples
A repo with Azure AI Cognitive Services Samples all compiled into a single repo leveraging the RESTClient plugin for VSCode.

## Usage
This repo is a work in progress but generally groups together a number of the examples shown in the Microsoft Docs website for Azure AI Cognitive Services.  The `*.http` files may all be opened up in VSCode and called directly from the GUI by installing the [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) add in.

## WARNING! 
**Do Not Check Keys Into Code!**
In order to prevent checking subscription keys into the demo files, please leverage the `Environments` feature of REST Client, which allows the developer to persist variables in VSCode's `settings.json` instead of in the HTTP files. 