
# About
A Vue component library based on CodyHouse UI. This package includes components for assembling website blocks and admin ui. This package was built using [vue-sfc-rollup](https://github.com/team-innovation/vue-sfc-rollup).


## Install from NPM

Just need to consume this package?

```bash
npm install
```


## Local Package Development
Contributing to this package? Clone it anywhere you keep your projects and work on the package like you would any typical Vue project.

Clone repository:

```bash
git clone https://github.com/heyharmon/vue-design-system.git
```

Install dependencies:

```bash
npm install
```

Start the server and watch changes:

```bash
npm run serve
```

View package dev screen at: http://localhost:7000


## Install Locally
If you want to use this package in another local Vue project, you can "link" it to that project. This creates a symbolic link from your other projects' node_modules to your local clone of this package. This way, changes to this package can immedietely be reflected in your other project.

From within this packages' directory, run:

```bash
npm link
```

From within your other project directory, run:

```bash
npm link @bloomcu/vue-design-system
```

Console will return this packages' path on your machine. Use the path to install this package locally:

```bash
npm install [the-path-local-package]
```

Now you can use the package like any other package you installed from NPM:

```js
<script>
    import { AppButton } from '@bloomcu/vue-design-system'
</script>
```


## Updating Package
When you are finished developing, semantically bump the version in package.json:

```json
// in package.json
{
    ...
    "version": "0.0.3",
    ...    
}
```

Build the package:

```bash
npm run build
```


## Publishing to NPM
You must be a user on BloomCU's NPM organization to publish new versions of the package. If you are not, you can submit a pull request to the repository and someone else will review your code and publish it to NPM.

Log into NPM:

```bash
npm adduser
```

Publish:

```bash
npm publish
```
