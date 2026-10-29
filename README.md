# Insightly

Insightly is a data-collection tool for a research project I am running. Its goal is to help researchers sign up, publish question banks, collect responses, view useful statistics, and access and download their data so they can draw conclusions more easily.

This public repository contains an exported frontend build of Insightly. The application is available on its own domain; the files here are generated assets rather than the original development source. The repository alone does not establish the security or availability of the underlying data services.

## View the project

[Open Insightly](https://insightly.space)

## Repository contents

- `index.html`: the frontend entry point.
- `assets/`: generated JavaScript and CSS bundles.
- `.github/workflows/`: configuration for publishing the copy to GitHub Pages.

The checked-in files are built assets rather than the original source code. Server-only code, private environment values, database contents, and deployment credentials are not included. Functionality depends on the services and configuration used by the frontend. The GitHub Pages deployment currently does not load the application correctly; use the official domain above.
