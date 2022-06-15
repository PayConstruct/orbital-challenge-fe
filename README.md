# Orbital Code Challenge
This challenge is designed for those that want to apply for Frontend Engineer position.

## Mandatory Technology
The following technologies must be used in the project:
* [React](https://reactjs.org/docs/getting-started.html)
* [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-tooling-in-5-minutes.html)
* [Redux-toolkit](https://redux-toolkit.js.org/introduction/getting-started)

As a company we aim for scalability and maintainability, so keep that in mind when coding components.

## Building the application:
We use CSS Modules to build components and we follow [BEM CSS Methodology](http://getbem.com/introduction/), so we encourage you to try it out.

You can decide to: 
* Build the application using CRA or Webpack / Rollup / Parcel or any other bundler you prefer.
* Use NPM or Yarn.

## The Challenge:
Build a "Accounts Page" that show "corporate accounts" and "custody vaults".
[Figma Design Mockup](https://www.figma.com/file/CbM9dFGtFvyRAgbPD6thmf/FE-interview-challenges?node-id=0%3A1) has the page structure you need to follow to build the application.

* Both "Corporate accounts" and "Custody vaults" load accounts with `currency`, `balance`, `accountName`, `accountType`. Use the same API to load accounts for both components, you can mock the API.
* You must use the assets provided to display the currency icon.
* Both "Corporate accounts" and "Custody vaults" initially load the maximum of 4 accounts.
* Clicking **See more** in "Corporate accounts" or "Custody vaults" components loads 8 more accounts.

* Both Buttons "+ New Account" and "+ New Transaction" must be present, but they have no functionality.

## Submitting your solution
Your code should run locally, you can deploy it as well.

**Create a Git Hub repository with your solution and share it with us when you finish.**

