

<h1 align="center">typescript-boilerplate</h1>

<div align="center">
	<strong>A quick-start Typescript project</strong>
</div>
<div align="center">
  <sub>
  	<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/1200px-Typescript_logo_2020.svg.png" height="20px" style="margin-top: 10px">
  </sub>
</div>
<br />

<div align="center">
  <a href="https://opensource.org/licenses/Apache-2.0">
  	<img src="https://img.shields.io/badge/license-apache_2-green.svg?style=flat-square">
  </a>
  <a href="https://github.com/Microsoft/TypeScript">
        <img src="https://img.shields.io/badge/typescript-4.7.2-blue.svg?style=flat-square">
  </a>
</div>

<div align="center">
  <h3>
    <a href="#dependencies">Dependencies</a>
    <span> | </span>
    <a href="#configuration">Configuration</a>
    <span> | </span>
    <a href="#commands">Commands</a>
  </h3>
</div>

## Dependencies

Pre-installed dependencies:

- [x] `tscpaths` for easily avoid local paths when importing files
- [x] `clear` for clean-up your console output
- [x] `eslint` for enforcing your code-style
- [x] `nodemon` for instant rebuild and re-run your project once a file has been changed

## Configuration


Clone this repository by using the following command

    $ npm clone https://github.com/AndreaVitale/typescript-boilerplate <your_project_name>

Edit `name` property inside `package.json` file and rename it with your project name.
Now open `tsconfig.json` file and add/edit/remove all possible path aliases you want to use in your project.


## Commands

- [x] `npm run build` will transpile your typescript files into javascript files and place them inside `build` directory
- [x] `npm run watch` start nodemon server and listen for any file changes and, once detected, rebuild the whole project
- [x] `npm run start` build and start the project entry file
- [x] `npm run start:dev` rerun the project entry file once a change is detected (useful if used with `watch` command)
