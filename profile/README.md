# usabl

usabl checks web UI changes for accessibility barriers during development, before they ship. The same engine runs from the command line, a browser overlay, an AI coding assistant, and a pull request check.

It is a preview release, version 0.2.1, built for Red Hat Innovation Days 2026.

## The code

All three repositories are public and licensed under Apache-2.0.

| Repository | What it holds |
|---|---|
| [usabl](https://github.com/usabl-dev/usabl) | The engine: the command line tool, the browser overlay, the assistant stop hook, and the pull request check. |
| [usabl-app](https://github.com/usabl-dev/usabl-app) | A small PatternFly app with accessibility barriers built in, and a walkthrough of usabl on it that takes about 20 minutes. |
| [usabl-plans](https://github.com/usabl-dev/usabl-plans) | The implementation plans behind each release. |

The barriers in usabl-app are deliberate. Do not use it as a PatternFly reference.
