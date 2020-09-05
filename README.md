# Phaser 3 template project

### Very simple, no unnecessary overhead, no need to credit, you can use it both for Typescript and Javascript projects.

Includes:

- Phaser 3
- Typescript
- ESLint set up for typescript
- Webpack with:
  - Bundling and minifying (including typescript)
  - Dev server
  - Dist cleaning before build
  - HTML template

I decided to create my own template project for Phaser 3, because most of them either outdated, or unnecessary complex. This template has bare minimum for comfortable phaser development with empty project inside.

# How to start

- Clone this repo: `git clone https://github.com/kmeshavkin/phaser-template.git`
- Install dependencies: `npm i`
- Develop app: `npm start`
- Build app: `npm build`

**NOTE:** By default during build webpack searches main.ts file, but if you want to use it with javascript, just replace `entry: './src/main.ts'` with `entry: './src/main.js'` in the `webpack.config.js` file.
