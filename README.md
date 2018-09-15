## Prerequisites:
- Install npm (v 5.x or greater)
- Install Node.js (v 8.x or greater)

## Local setup:
- Clone this repository
- Rename package.example.json -> package.json
- Run `npm i`

## Useful commands:
- `npm run new -- [appname]` - Creates a new directory and a new Angular app
- `npm run serve` - Builds and serves your app, rebuilding on file changes
- `npm run generate -- [directive|pipe|service|class|guard|interface|enum|module] [name]`- Generates a specific schematic, also covers them with test shells

NOTE : Since we are using Angular CLI locally the above commands execute the following commands:

- `ng new [appname]`
- `ng serve --open`
- `ng generate directive|pipe|service|class|guard|interface|enum|module [name]`

## Additional information
To get more help on the Angular CLI use `npm run ng -- help`/`npm run ng -- [command] --help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md)