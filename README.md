# Orbital Code Challenge
This challenge is designed for thouse that want to apply for Frontend Engineer position.

## Mandatory Technology
The following technologies must be used in the project:
* React (https://reactjs.org/docs/getting-started.html)
* Typescript (https://www.typescriptlang.org/docs/handbook/typescript-tooling-in-5-minutes.html)
* Redux-toolkit (https://redux-toolkit.js.org/introduction/getting-started).

As a company we aim for scalabilty and maintainability, so keep that in mind when coding components.

## Building the application:
We use CSS Modules to build components and we follow CSS BEM Methodology (http://getbem.com/introduction/), so we encorage you to try it out.

You can decide to: 
* Build the application using CRA or Webpack / Rollup / Parcel or any other bundler you prefer.
* Use NPM or Yarn.

## The Challenge:
Build a "Accounts Page" that show "corporate accounts" and "custody vaults".
The following link ---------- leads to a figma design mockup that you must follow to build the page.

* Both "Corporate accounts" and "Custody vaults" load accounts with `currency`, `balance`, `accountName`, `accountType`. Use the same API to load accounts for both components, you can mock the API.
* You must use the assets provided to display the currency icon.
* Both "Corporate accounts" and "Custody vaults" initially load the maximum of 4 accounts.
* Cliking **See more** in "Corporate accounts" or "Custody vaults" components loads 8 more accounts.

* Both Buttons "+ New Account" and "+ New Transaction" must be present, but they have no functionality.

## Submitting your solution
Submit a Github PR with your name as title.
You can add comment if you wish to do so
