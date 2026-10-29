# Insightly — frontend build

Insightly is a data-collection tool for a research project I am running. Its goal is to help researchers sign up, publish question banks, collect responses, view useful statistics, and access and download their data so they can draw conclusions more easily.

This repository contains a copy of the production frontend served for Insightly. It provides the deployed browser files for viewing the interface; it is not the original development source repository. The repository alone does not establish the security or availability of the underlying data services.

## View the project

- [Open Insightly](https://insightly.space)
- [Open the GitHub Pages copy](https://fsrkh12-arch.github.io/insightly/)

## Repository contents

- `index.html`: the frontend entry point.
- `assets/`: generated JavaScript and CSS bundles.
- `.github/workflows/`: configuration for publishing the copy to GitHub Pages.

The checked-in files are built assets rather than the original source code. Server-only code, private environment values, database contents, and deployment credentials are not included. The public copy's full functionality depends on the services and configuration used by the frontend; this repository alone does not establish that every feature is available.
