# css-loader-repro-file-protocol

## Issue

Encountered https://github.com/webpack-contrib/css-loader/issues/1362 but tweaking all the configs couldn't solve my issue. Apparently there's some minimum version needed for webpack. Found using trial and error that need at least webpack 5.23.0 so that the final output would be correct

## Running repro

- clone repo
- `yarn install`
- `yarn build`

## When using webpack@5.22.0

![Screenshot 2021-09-29 at 3 54 28 PM](https://user-images.githubusercontent.com/3090380/135227417-b7e87705-33c1-40ba-ad4b-de13d3c338aa.png)

## When using webpack@5.23.0

![Screenshot 2021-09-29 at 3 54 43 PM](https://user-images.githubusercontent.com/3090380/135227431-cebe6536-9b2a-44a4-8a8c-28078dce7bdd.png)
