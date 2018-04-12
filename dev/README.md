# Development Zone!

Hey 184 group! :D

## Current Status

Node.js setup seems to require quite a lot of troubleshooting. Basically it's been solving a train of bugs. 

The current hitch:

- `Syntax error: unexpected character on line 1, '<'`

I expect it may be a problem with Firefox and am currently troubleshooting. Feel free to jump in. 

## Solutions to Old Bugs

Getting started:

- `npm install`
- `npm start`

The browser may raise an error involving `events.js:183`. If it does:

- `rm -rf node_modules`
- `npm install`

May also encounter uninstalled dependencies:

- `npm install --save 'name of dependency'`

Haven't figured out a way to automatically get dependencies yet. Happy noding!
