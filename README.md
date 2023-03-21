# helm-diff-npm

NPM Wrapper around helm plugin [helm-diff](https://github.com/databus23/helm-diff).

Installs the helm-binary along with the diff plugin such that it's useable
by node projects.

## Installation

Install helm 3 and the helm diff plugin with one line:

```bash
yarn add global helm-diff-npm
```

This should allow you to run helm from your command line assuming you have
the `npm bin` or equivalent in your $PATH

```bash
export PATH=$(npm bin):$PATH
$ which helm
/node_modules/.bin/helm

$ helm plugin list
NAME  VERSION  DESCRIPTION
diff  3.1.3  Preview helm upgrade changes as a diff

```

## See also

Package is available on [npmjs](https://www.npmjs.com/package/helm-diff-npm)
