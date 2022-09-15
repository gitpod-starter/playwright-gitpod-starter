# playwright-gitpod-starter
Gitpod starter for running playwright
---

**.gitpod.Dockerfile:** 
- added the image for node (FROM gitpod/workspace-node)

**.gitpod.yml:**
- link the docker image created
- on the init task run the following commands 
  - `npm install playwright`: intalling the tool
  - `npm install create-playwright`: plugin to craete your playwright project with a single command
  - `npm init playwright@latest`: setup a new or existing npm project
  - `npx playwright install-deps`: installing the system dependencies
  - `npm install -D @playwright/test`: Run mocha, zora, uvu, tape and benchmark.js scripts inside real browsers with playwright

