# react-vtkjs-viewport-custom

> This is a copy from original `react-vtkjs-viewport`. This changes the strategy
> of bundling packages. I.e. it bundles vtkjs within it. VTK.js image viewport
> component for React

For more details go to:
[![NPM](https://img.shields.io/npm/v/react-vtkjs-viewport.svg)](https://www.npmjs.com/package/react-vtkjs-viewport)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FOHIF%2Freact-vtkjs-viewport.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FOHIF%2Freact-vtkjs-viewport?ref=badge_shield)

## Install

```bash
# With NPM
npm install --save react-vtkjs-viewport-custom

# With Yarn
yarn add react-vtkjs-viewport-custom
```

## Development

Local development uses `<root>/examples` as a test application. You can import
the VTK Viewport using a WebPack alias like so:

`import VtkViewport from '@vtk-viewport'`

Any updates to the example files or the VtkViewport's source will cause WebPack
to rebuild.

```bash
# Restore Dependencies
yarn install

# Start Local Dev Server
yarn run dev
```

## License

MIT © [OHIF](https://github.com/OHIF)
