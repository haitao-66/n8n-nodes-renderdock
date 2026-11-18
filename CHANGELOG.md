# 0.1.5

Fix two runtime bugs found during demo recording:

- Export name now matches the loader's expectation (`Renderdock` for `Renderdock.node.js`); nodes failed to load under the old casing
- Template data is parsed when n8n returns the JSON field as a string
# 0.1.4

Move to a dedicated repository (github.com/haitao-66/n8n-nodes-renderdock) with the package at the repo root, matching n8n vetting expectations.
# 0.1.3

Commit built dist artifacts to the repository (n8n vetting requires declared files present in the repo).
# 0.1.2

Restructure node into the resource/operation pattern required by n8n verification.

- Resource options (Markdown, HTML, URL, Template) with action labels
- Single Render operation
# 0.1.1

Initial TypeScript release on the official @n8n/node-cli scaffold.

- Node rewritten in TypeScript with strict mode
- Dark mode icon
- Credential connection test
- Published via GitHub Actions with npm provenance
