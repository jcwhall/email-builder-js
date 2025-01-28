<div align="center">
  <h1>EmailBuilder.js Fork - Support Embedding Local Image Files in HTML Files.</h1>
</div>

## Overview
Implemented <a href="https://github.com/usewaypoint/email-builder-js/issues/98">Feature Request #98</a> - Support Embedding Local Image Files in HTML Files. 
- Applies to the Self Hosted Editor
- Images can now be uploaded from the local file system, rather than the current system using URLs (links to externally hosted images)
- These images are base64 encoded and set as the img src
- The encoded image is stored within the HTML/JSON and works as before (Import/Export, etc)

<br>


## Self hosting the Editor

Fork this repository and use [packages/editor-sample](https://github.com/usewaypoint/email-builder-js/tree/main/packages/editor-sample) as an example for self-hosting.

Quick start:

1. Fork this repository.
2. Open up directory in terminal.
3. Go to the editor-sample package: `cd packages/editor-sample`
4. Install packages: `npm install`
5. Run the server: `npx vite`
6. Open in browser: http://localhost:5173/email-builder-js/

---

For more information:
<p>
    <a href="https://usewaypoint.github.io/email-builder-js/#sample/reservation-reminder">Demo / Playground</a>&emsp;&middot;&emsp;
    <a href="https://www.emailbuilderjs.com">EmailBuilderJS.com</a>&emsp;&middot;&emsp;
    <a href="https://github.com/usewaypoint/email-builder-js">GitHub</a>
  </p>
