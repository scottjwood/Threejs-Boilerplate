# Three.js Boilerplate

A Three.js Boilerplate to aid in quick prototyping.

When updating older Three.js projects, you may get a warning in the browser such as,
"As part of the transition to ES6 Modules, the files in 'examples/js' were deprecated in May 2020 (r117) and will be deleted in December 2020 (r124)."

There are several steps involved in converting to use modules. This boilerplate was written to help you solve some issues that you may have when converting your Three.js projects to use modules.

To install and start the master (ES6) branch

```bash
git clone https://github.com/Sean-Bradley/Threejs-Boilerplate.git
cd Threejs-Boilerplate
npm install
npm start
```

Visit http://127.0.0.1:3000

To update threejs

```
npm install three@latest
```

**Note** : This boilerplate contains 3 branches

-   master : The minimal boilerplate using ES6 imports and script type module
-   before-es6-modules : The example, but using older style script imports
-   water : An example based on the official [Three.js Ocean example](https://threejs.org/examples/?q=water#webgl_shaders_ocean)

To see the `before-es6-modules` branch

```bash
git checkout before-es6-modules
npm install
npm start
```

To see the `water` branch

```bash
git checkout water
npm install
npm start
```

![Water Branch](docs/water.jpg)

### Video Tutorial About Importing Three.js as Module

[![Importing Three.js as Module](https://img.youtube.com/vi/z9qtGHTqLqQ/0.jpg)](https://youtu.be/z9qtGHTqLqQ)

<!-- prettier-ignore -->