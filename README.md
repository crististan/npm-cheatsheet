# NPM Cheatsheet
Table of contents
  * [General commands](#general-commands)
  * [Check the npm version](#check-the-npm-version)
  * [Install packages](#install-packages)
  * [Update packags](#update-packages)
  * [Uninstall packages](#uninstall-packages)
  * [Install frameworks](#install-frameworks)
      * [Vite](#vite)
      * [React](#react)
      * [Vue](#vue)
      * [Svelte](#svelte)
      * [Astro](#astro)
   * [Other packages](#other-packages)
     * [Sass](#sass)
     * [Bootstrap](#bootstrap)
     * [Tailwind](#tailwind)
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
Run the scripts defined scripts in the package.json file
```
npm run <script_name>
```
## Install packages
Install a package
```
npm i <package_name>
```
```
npm install <package_name>
```
Install a package globally
```
npm install -g <package_name>
```
Install a package as a production dependency
```
npm install --save <package_name>
```
Install a package as a development dependency
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
## Update packages
Update a package
```
npm update <package_name>
```
Update a package globally
```
npm update -g <package_name>
```
Update a package as a production dependency
```
npm update --save <package_name>
```
Update a package as a development dependency
```
npm update --save-dev <package_name>
```
## Uninstall packages
Uninstall a package
```
npm uninstall <package_name>
```
Uninstall a package globally
```
npm uninstall -g <package_name>
```
Uninstall a package as a production dependency
```
npm uninstall --save <package_name>
```
Uninstall a package as a development dependency
```
npm uninstall --save-dev <package_name>
```
## Install frameworks
### Vite
```
npm create vite@latest
```
Specify the project name and the template you want to use
```
npm create vite@latest <app_name> --template <template_name>
//as template you can use vanilla, vue, react, preact, lit, svelte
```
### React
```
npm init vite

# Then select react as template
```
### Vue
```
npm init vue@latest
```
### Svelte
Install Sveltekit
```
npm create svelte@latest <app_name>
```
Install Svelte (via Vite)
```
npm init vite

# Then select svelte as template
```
### Astro
```
npm create astro@latest
```
## Other packages
### Sass
```
npm install -g sass
```
```
npm install --save-dev sass
```
### Bootstrap
```
npm install bootstrap
```
### Tailwind
```
npm install -D tailwindcss
npx tailwindcss init
```
