# Sparki

CI that gets out of your way. In public beta.

Start a pipeline from a template, run each build in an isolated container, and when one fails, Sparki names the cause and the change that fixes it.

**[Start free at sparki.tools](https://sparki.tools)**

## Try it in three steps

1. Sign in and open **Projects → New Project**.
2. Add a sample repository, and create a pipeline from its starter.
3. Trigger a build. `main` goes green. Branch `fail` goes red, so you can see a failure explained.

| Sample | Starter |
| --- | --- |
| [sample-node](https://github.com/sparki-tools/sample-node) | Node.js |
| [sample-python](https://github.com/sparki-tools/sample-python) | Python |
| [sample-go](https://github.com/sparki-tools/sample-go) | Go |

## What it does today

- Node.js, Go and Python templates, or one command of your own
- Isolated containers on a dedicated build worker
- Live build logs in the browser
- Failure diagnosis, with a suggested fix

## What to expect in beta

- Public repositories only, for now
- One build worker: builds run one after another, first come, first served
- Each step can run for up to 30 minutes

## Get in touch

Questions: [hello@sparki.tools](mailto:hello@sparki.tools). Security: see our [security policy](https://github.com/sparki-tools/.github/blob/main/SECURITY.md).

Sparki is built by Devarno Ltd.
