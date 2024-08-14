# gatsby-plugin-glslify

(This fork fixes a bug with the version of gatsby it uses)
A Gatsby plugin to be able to import glsl/vert/frag files, and have them processed by [glslify](https://github.com/glslify/glslify).

## Installation

`npm install --save glslify gatsby-plugin-glslify`

## Usage

```javascript
// In your gatsby-config.js
module.exports = {
  plugins: `gatsby-plugin-glslify`,
}
```
