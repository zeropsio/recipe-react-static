# Zerops x React - Static

React is a javascript web library for building fast , dynamic full-stack web apps with both server-side rendering and static site generation. <a href="https://zerops.io/" target="_blank">Zerops</a> makes deploying and running React apps, both server side rendered and static, a breeze.

This recipe showcases the SSG version, see [zeropsio/recipe-react-nodejs](https://github.com/zeropsio/recipe-react-nodejs) for the SSR Node.js version.

![react](https://github.com/zeropsio/recipe-shared-assets/blob/main/covers/svg/cover-react.svg)

<br/>

## Deploy to Zerops

You can either click the deploy button to deploy directly on Zerops, or manually copy the [import yaml](https://github.com/zeropsio/recipe-react-static/blob/main/zerops-project-import.yml) to the import dialog in the Zerops app.

[![Deploy on Zerops](https://github.com/zeropsio/recipe-shared-assets/blob/main/deploy-button/green/deploy-button.svg)](https://app.zerops.io/recipe/react-static)

<br/>

## Recipe features
- Latest version of **React + Vite** with SSG running on a load balanced **Zerops Static** service.

<br/>

## Production vs. development
This recipe is ready for production as is, and will scale horizontally by adding more containers in case of high traffic surges. If you want to achieve the highest baseline reliability and resiliace, start with at least two containers (add `minContainers: 2` in recipe YAML in the `app` service section, or change the minimum containers in "Automatic Scaling configuration" section of service detail).

<br/>

## Changes made over the default installation
If you want to modify your existing React app to efficiently run on Zerops, there are no changes needed in the codebase on top of the standard installation, just add [zerops.yml](https://github.com/zeropsio/recipe-react-static/blob/main/zerops.yml) to your repository.

<br/>
<br/>

Need help setting your project up? Join [Zerops Discord community](https://discord.com/invite/WDvCZ54).
