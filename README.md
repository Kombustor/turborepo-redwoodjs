# Turborepo + RedwoodJS example

This is a WIP proof-of-concept for multiple RedwoodJS projects in a single Turborepo-powered Monorepo.

## What's inside?

This turborepo uses [Yarn](https://classic.yarnpkg.com/lang/en/) as a package manager. It includes the following packages/apps:

### Apps and Packages

- `admin`: the first RedwoodJS app
- `app`: the second RedwoodJS app
- `ui`: a stub React component library shared by both `admin` and `app` applications
- `eslint-config-custom`: `eslint` configurations (includes `eslint-config-prettier`)
- `tsconfig`: `tsconfig.json`s used throughout the monorepo