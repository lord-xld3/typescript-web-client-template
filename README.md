# typescript-web-client-template

Clone this and add assets. Run following commands in PowerShell.

## 1. Setup TypeScript/npm workaround (one-time)

Install typescript compiler
>`npm install -g typescript`

Next line **must** be run in an admin Powershell window
>`Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine`

## 2. (Optional)

Install jQuery
>`npm install --save @types/jquery`

## 3. Usage

### Start Compiler in /src/

Run once, it will compile whenever you save a .ts file
>`tsc -p .\tsconfig.json`

### /src/script.ts

Write program here, it will compile to ../build/script.js

### /src/tsconfig.json

Defaults: target ES6, remove comments, strict type checking