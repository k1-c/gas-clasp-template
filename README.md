# GAS Clasp Template
> Super Cool Template for Google Apps Script Development on local

## Features
- Quick Starting to local development (just configure for your project)
- Clasp (on GitHub Actions. not required on developers other than GAS owner)
- GitHub Actions (Auto Deployment)
- TypeScript with types/google-apps-script

## Installation on your project
- Install Clasp<br>
  `npm install -g @google/clasp`
- Get your Script ID
  - You can check your id on ScriptEditor > File > Property > Script ID
- [Enable Google Apps Script API](https://script.google.com/home/usersettings)
- Clasp login<br>
  `clasp login`
- Set your Script ID in `.clasp.json`
- Remove Sample file (`src/main.ts`)
- Pull your project

## Configuration for Auto Deployment
- Clasp login<br>
  `clasp login`
- Check your credentials<br>
  `cat ~/.crasprc.json`
- Set your secrets to your GitHub repository
