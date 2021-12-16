# Demo for Playwright and Lighthouse CI

This repository is a sample test about using Playwright to automate a browser, launch Lighthouse audits on the pages and then sending them to a remote Lighthouse CI Server.

For deploying a Lighthouse CI Server [check this document](https://github.com/GoogleChrome/lighthouse-ci/blob/main/docs/getting-started.md#the-lighthouse-ci-server).
## Build and run

1. Clone the repository and install dependencies:

```bash
npm i
```
2. Fill the lighthouserc.js with the proper information (demo file present at the repo).
3. Run the tests:

```bash
npm test
```