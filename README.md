# Sharegate Browserslist config

Sharegate shared [Browserslist](https://github.com/browserslist/browserslist) config.

## Installation

Install the package.

With NPM:

```bash
npm i -D @sharegate/browserslist-config-recommended
```

Create a `.browserslistrc` file at the root of your project.

Add the following configuration:

```
extends @sharegate/browserslist-config-recommended
```

## Maintainers

The following documentation is only for the maintainers of this repository.

### Installation

Clone the repository:

```bash
git clone https://github.com/gsoft-inc/sg-browserslist.git
```

Then, install the dependencies with Yarn:

```bash
yarn install
```

### Release

Before you release, make sure you have **write access** for all the NPM packages that will be published and that you are [logged in to NPM](https://docs.npmjs.com/logging-in-to-an-npm-enterprise-registry-from-the-command-line).

To release, open a terminal at the root project of the workspace and execute the following:

```bash
yarn release
```

## License

Copyright © 2019, Groupe Sharegate inc. This code is licensed under the Apache License, Version 2.0. You may obtain a copy of this license at https://github.com/gsoft-inc/gsoft-license/blob/master/LICENSE.
