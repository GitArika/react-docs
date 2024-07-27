# Builds and compilers

## About

Builders and compilers can convert your code to backwards version. This enable compatibility with multiple browsers, even if they are running at an outdated version.

## Compilers

Tools that convert your code from a format to another, downgrading features that is not supported or aiming older versions.

The most used compilers:

- Babel

## Bundlers

Usually we don't want to write all code in a single file, the most common pattern is to decouple our code base within mutiple files that references each other. But it's not supported in all browser versions. The solution was to use bundlers that join all your modules and files in a single javascript file.

The most used compilers is Webpack. Webpack also generate the static assets such as images or styles.

## Can I use

[Can I Use](caniuse.com)

Is a website that tracks compatibility for browser features.

## Up to date tools

Recently tools was created for easily distribute your webapp accross multiple browser versions using on demand native ecmascript modules and not use bundlers. Eg:

- Vite (Also include an internal compiler)
- Snowpack