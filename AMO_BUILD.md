# Locky Firefox build instructions

Locky is based on the Bitwarden clients repository.

## Requirements

- Windows 10/11 or Linux/macOS
- Node.js 24
- npm

## Build

From the repository root:

npm install

Then:

cd apps/browser
npm run build:prod:firefox

The Firefox extension is generated in:

apps/browser/build/
