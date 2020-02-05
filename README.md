[![Board Status](https://dev.azure.com/nrogoff-avanade/50d86c29-d346-4123-af6d-188b0b5e9c8c/f63edfaa-9482-43d3-8747-3697b8b4efc7/_apis/work/boardbadge/4df11f9a-a062-418c-a8b1-923c5cfb13cb)](https://dev.azure.com/nrogoff-avanade/50d86c29-d346-4123-af6d-188b0b5e9c8c/_boards/board/t/f63edfaa-9482-43d3-8747-3697b8b4efc7/Microsoft.RequirementCategory)
## Welcome

This repository contains the base project part of our on-site GitHub Verified Partner workshop program. It is meant to be used for in-classroom training under the supervision of GitHub coaches.

This is the NodeJS version of our "Tonkotsu" workshop webapp. The codebase is pretty simple: it's a NodeJS app that will connect to GitHub's [Octocat API endpoint](https://api.github.com/octocat) and return the Zen quote of the day. E.g.:

### Demo (sucess)

![out](https://user-images.githubusercontent.com/1078545/57860397-bc7ff380-77ec-11e9-80f8-39e02ef3c035.gif)


### Demo (failure)

![out](https://user-images.githubusercontent.com/1078545/57860396-bc7ff380-77ec-11e9-8f55-83b879e667d2.gif)


There are some built-in unit tests to ensure that everything can be verified.

### Instructions

Please fork this repository and ensure you have a local working copy. You will need a working NodeJS environment. Get the latest stable version from https://nodejs.org/en/download/ or via your OS package manager (e.g. `brew` on Mac or `chocolatey` on Windows). 

Setup:

```
npm install 
```

Tests:

```
npm run test
```

Run server (defaults to localhost:3000):

```
npm start
```

Follow the coach instructions and good luck!
