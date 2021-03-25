# Applitools Tutorial - Images in JavaScript

Get started with automated visual testing using the Applitool Eyes Images SDK.

## Pre-Requisites
* Install Node.js from [here](https://nodejs.org/en/)

## Run the Example Project
1. Download the example
    * Option 1: `git clone https://github.com/applitools/tutorial-images-javascript.git`
    * Option 2: Download it as a Zip file and extract it
2. CD into the `tutorial-images-javascript` folder
3. Set up environment variable `APPLITOOLS_API_KEY` with your own API key.
    * Login to Applitools > Click on the Person icon > My API Key
    * Linux/Mac: export APPLITOOLS_API_KEY=<your_key>
    * Windows: set APPLITOOLS_API_KEY=<your_key>
4. run `npm install`
5. run `npm test`


## Add Applitools Eyes to an Existing Node.js Project

Install the Applitools Eyes Images SDK:

```
npm install @applitools/eyes-images --save-dev
```

Follow along with the example in this repository for adding Applitools Eyes along with your existing tests.

## GitHub Action CI/CD Example

This repository includes an example of how you can integrate Applitools Eyes into your CI/CD process whether with GitHub Actions or a variety of other tools:

https://github.com/applitools/tutorial-images-javascript/blob/main/.github/workflows/test.yml

## Eyes Images SDK tutorial

Find the tutorial at: https://applitools.com/tutorials/screenshots-javascript.html

## More Information
* https://www.npmjs.com/package/@applitools/eyes-images
* https://applitools.com/docs/api/eyes-sdk/index-gen/classindex-images-javascript.html
