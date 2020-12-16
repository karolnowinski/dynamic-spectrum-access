# Dynamic Spectrum Access

## About
This project implements a graphical interface for the project carried out as part of the course at the university.

The application uses the following libraries.
| Library | Homepage |
| ------ | ------ |
| Chart.js | [chartjs.org](https://www.chartjs.org/) |
| Bootstrap | [getbootstrap.com](https://getbootstrap.com/) |

## Dependencies

The project requires [Node.js](https://nodejs.org/) and uses the following packages:
- babel
- browser-sync
- eslint
- node-sass
- onchange
- parallelshell

## Development

Install the devDependencies.

```sh
$ npm install
```

##### Run
To run the project, use the command below:
```sh
$ npm start
```

##### Build
The project uses *node-sass* and *eslint* to build scss and js files. This is done using the following commands:

```sh
$ npm run build:scss
```
```sh
$ npm run build:js
```

The following commands are used to watch changes in project files and build these files:

```sh
$ npm run watch:scss
```
```sh
$ npm run watch:js
```
```sh
$ npm run watch:all
```