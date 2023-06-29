# NPM Cheatsheet
## General commands
Create a package.json file
```
npm init
```
Create a package.json file with default values
```
npm init -y
```
```
npm init --yes
```
Install all modules listed as dependencies in package.json to the local node_modules folder
```
npm install
```
### Check the npm version
```
npm -v
```
```
npm --version
```
## Install package
Install package
```
npm i <package_name>
```
```
npm install <package_name>
```
Install the package globally
```
npm install -g <package_name>
```
Install the package as a production dependency
```
npm install --save <package_name>
```
Install the package as a development dependency
```
npm install --save-dev <package_name>
```
Install a specific version of the package globally
```
npm install -g <package_name>@<package_version>
```
Install a specific version of the package as a production dependency
```
npm install --save <package_name>@<package_version>
```
Install a specific version of the package as a development dependency
```
npm install --save-dev <package_name>@<package_version>
```
## Install frameworks
### Svelte
```
npm create svelte@latest <app_name>
```
