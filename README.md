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

### Start Compiler

Run once, it will compile whenever you save a .ts file
>`tsc -p .\tsconfig.json`

### /src/lib.d.ts

Declare type definitions here (optional, makes script.ts cleaner), don't assign values

### /src/script.ts

Write program here, it will compile to .js