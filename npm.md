# NPM Tips & Tricks

## Overview
Node Package Manger (NPM) is a package manager used with NodeJS

## Basics

### Getting help from NPM 

`npm -h`

To know in detail about a command 
`npm install -h`

To view the documentation on the command
`npm help install`

To view the list of all help topics 
`npm help-search remove`

List all user config
`npm config ls`

list all config values
`npm config ls -l`


### [NPM Shortcuts](https://docs.npmjs.com/misc/config)

The following shorthands are parsed on the command-line:

- -v: --version
- -h, -?, --help, -H: --usage
- -s, --silent: --loglevel silent
- -q, --quiet: --loglevel warn
- -d: --loglevel info
- -dd, --verbose: --loglevel verbose
- -ddd: --loglevel silly
- -g: --global
- -C: --prefix
- -l: --long
- -m: --message
- -p, --porcelain: --parseable
- -reg: --registry
- -f: --force
- -desc: --description
- -S: --save
- -P: --save-prod
- -D: --save-dev
- -O: --save-optional
- -B: --save-bundle
- -E: --save-exact
- -y: --yes
- -n: --yes false
- ll and la commands: ls --long

### Creating packages

Create a NodeJS project
`npm init` 

Create project with default settings
`npm init -y`

Set Defaults for npm 
`npm set init-author-name 'Costa Ivo'`
`npm set init-license`

View Defaults for npm 
'npm get init-author-name`

Remove config
`npm config delete init-author-name`

### Installing packages

npm install [packageName]

npm install [packageName] --save
npm install [packageName] -S

npm install [packageName] --save-dev
npm install [packageName] -D


https://app.pluralsight.com/player?course=npm-playbook&author=joe-eames&name=npm-playbook-m1&clip=8&mode=live


## Advance

### Publishing your own Package 
