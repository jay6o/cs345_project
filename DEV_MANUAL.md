# Developer Manual

## Setup
Clone the repo and install dependencies (replace anything in <> with their proper values).
`git clone <repo> && cd <./repo> && npm install`

## Usage
- Run the project by starting up the Live Server extension on VS Code.  
**or**
- Start your own server with Python: `python3 -m http.server -d /src`.

## Unit Testing
Jest has been added as a developer dependency through npm, and tests have been configured to run with `npm test`.
You can also test individual files with `jest <test-file>` if you have Jest installed globally.

Writing tests with Jest is extremely simple, you can read more about writing tests [here](https://jestjs.io/docs/getting-started).

## Contributing
Learn how to contribute to the project [here](https://github.com/jay6o/cs345_project/blob/main/CONTRIBUTING.md).
