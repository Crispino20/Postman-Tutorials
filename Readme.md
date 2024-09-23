# How to create your own API

## Introduction 
Creating your own API gives you the flexibility to add, modifiy and delete objects at will. 

## Pre-requisites

To create your own API, you need to do the following:
- Install [NodeJS](https://nodejs.org/en/download/prebuilt-installer)
  - Installing this will inadvertently install **npm** (node package manager), which is required for creating and running you API
  - To check if node is already installed, open cmd terminal and type in `node --version`. If it exists, you will see the version number, otherwise you will receive an appropriate error message.
  - To check if npm is already installed, type in `npm --version` in the terminal. If it exists, you will see the version number, otherwise you will receive an appropriate error message.
- JSON-server
  - This is installed using npm
  - In the terminal, enter the following command `npm install -g json-server`
  - If you've already createed a json file, then enter the following command to create the API from your json file `json-server file_name.json`
  - Once the URL is generated in the command line, copy and paste it in your browser to view the existing content. At this point you can now send requests via Postman
