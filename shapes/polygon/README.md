[![banner](https://particles.js.org/images/banner2.png)](https://particles.js.org)

# tsParticles Polygon Shape

[![jsDelivr](https://data.jsdelivr.com/v1/package/npm/tsparticles-shape-polygon/badge)](https://www.jsdelivr.com/package/npm/tsparticles-shape-polygon)
[![npmjs](https://badge.fury.io/js/tsparticles-shape-polygon.svg)](https://www.npmjs.com/package/tsparticles-shape-polygon)
[![npmjs](https://img.shields.io/npm/dt/tsparticles-shape-polygon)](https://www.npmjs.com/package/tsparticles-shape-polygon)

[tsParticles](https://github.com/matteobruni/tsparticles) additional polygon shape.

## How to use it

### CDN / Vanilla JS / jQuery

The CDN/Vanilla version JS has one required file in vanilla configuration:

Including the `tsparticles.shape.polygon.min.js` file will export the function to load the shape:

```javascript
loadPolygonShape;
```

### Usage

Once the scripts are loaded you can set up `tsParticles` and the shape like this:

```javascript
loadPolygonShape(tsParticles);

tsParticles.load("tsparticles", {
  /* options */
  /* here you can use particles.shape.type: "polygon" */
});
```

### ESM / CommonJS

This package is compatible also with ES or CommonJS modules, firstly this needs to be installed, like this:

```shell
$ npm install tsparticles-shape-polygon
```

or

```shell
$ yarn add tsparticles-shape-polygon
```

Then you need to import it in the app, like this:

```javascript
const { tsParticles } = require("tsparticles-engine");
const { loadPolygonShape } = require("tsparticles-shape-polygon");

loadPolygonShape(tsParticles);
```

or

```javascript
import { tsParticles } from "tsparticles-engine";
import { loadPolygonShape } from "tsparticles-shape-polygon";

loadPolygonShape(tsParticles);
```
