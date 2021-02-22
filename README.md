# Hull Unification-as-a-Service (UaaS)

![Node.js CI](https://github.com/hull/hull-uaas/workflows/Node.js%20CI/badge.svg)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## Overview

The Hull Unification-as-a-Service (UaaS) connector aims to make unification and normalization more straightforward for the end-user by abstracting code away and providing a user interface to configure common scenarios.

Please refer to the end-user documentation for further details, see [Connector Docs](./assets/readme.md).

## Usage

After installing dependencies via

```console
npm i
```

you can use the `build` script from `package.json` to build the JS files or start the live development server running

```console
npm run start-src--watch
```

For convenience the script section contains a script to run `ngrok` and provide a tunnel to your local environment. Make sure to have [ngrok](https://ngrok.com/) installed and then run

```console
npm run ngrok
```

If you are not on a paid ngrok plan, you can run `ngrokfree` which doesn't use a dedicated subdomain.

To run a clustered version of the connector for production, use

```console
npm run start
```

## Contributing

This project welcomes contributions and suggestions; we would appreciate if you follow the [Code of Conduct](./CODE_OF_CONDUCT.md).

Please read the [Contribution Guidelines](./CONTRIBUTING.md) and refer to the [Developing Guidelines](./DEVELOPING.md) for details about how to make a positive impact on this project.

## Changelog

The changelog which details the releases can be found [here](./CHANGELOG.md).

## License

MIT License. See [LICENSE document](./LICENSE) for details.