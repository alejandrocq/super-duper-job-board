# Super Duper Job Board

## Fast Merges!
Want to start contributing quickly to a project? Here you go! I'm available often to merge PR's. Check out the quick [contributing documentation](contributing.md).

## Prerequisites

- Node v8.0.0 or higher

## How to run the app?

1. Clone the repo.
2. Run ```npm install``` or ```yarn install``` in terminal.
3. Run ```npm start``` or ```yarn start``` in terminal.
4. Navigate to ```localhost:3000``` in your browser.

## What the heck is this?
Basically, the idea behind this stems from my partner needing a way for her to show available jobs in her industry. These jobs would ultimately be created by people/companies who have open positions. It's pretty similar to Craigslist, but in this case entries would need to be approved and paid for, which would also require some integration with a payment system.

## User Stories

### Story 1:
As the provider of the job board, I want to display available job opportunities within my industry.

### Story 2:
As the provider of the job board, I want people with available jobs to post their opportunities on my board.

### Story 3:
As the provider of the job board, I want to approve/deny incoming job post requests.

### Story 4:
As the provider of the job board, I want to accept monetary compensation for displaying a job poster's opportunity.

## MVP
The project's minimimum viable product should be pretty simple. We won't worry about persistent storage solutions and any other backend service components. This will, for the time being, be a frontend React-based endeavor. Here are some **basic feature goals**:

- General header in which anyone can incorporate their own image/messaging
- General footer in which anyone can incorporate their own image/messaging
- Interface that displays job postings provided by hard-coded or api-sourced data
- Interface that enables users to create job postings

## Recommended Features
- Use [Redux](https://redux.js.org/basics/usagewithreact) and [Redux-thunk](https://github.com/reduxjs/redux-thunk) for state management and async call to API
- Use [Error Boundaries](https://reactjs.org/docs/error-boundaries.html) to handle App error
- Use [eslint](https://eslint.org/), [prettier](https://prettier.io/) with [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb) for automatic and better code formatting
- Use [Material-ui](https://material-ui.com/) or [Ant design](https://ant.design/) or any component framework

## License

Active Record is released under the MIT license:

* https://opensource.org/licenses/MIT


