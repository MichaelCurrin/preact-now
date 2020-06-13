![Preact Logo](https://github.com/zeit/now/blob/master/packages/frameworks/logos/preact.svg)

# Preact Now Quickstart

This is brief example of a [Preact](https://preactjs.com/) app that can be deployed with Vercel and zero configuration.

Demo site: 

- https://preact-now.michaelcurrin.now.sh

New to Preact? See the [Getting started](https://preactjs.com/guide/v10/getting-started) guide.


## Requirements

- [vercel.com](https://vercel.com) account - previously known as Now
- Local dev:
    - Node.js / NPM
    - [Vercel CLI](https://vercel.com/download) NPM package - to create project and to push deploys


## Setup your own

Create and deploy your own Preact project hosted on Vercel as a server-side application - great for SESO.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/zeit/now/tree/master/examples/preact)

That uses the Preact example in the [zeit/now](https://github.com/zeit/now) repo.

Here is their live sample: 

- [preact.now-examples.now.sh](https://preact.now-examples.now.sh)


## Create a fresh project

Use this project as a template, or get started with Preact for deployment with Vercel, you can use the [Preact CLI](https://github.com/preactjs/preact-cli) to initialize the project:

```shell
$ preact create default my-project
```


## Deploy

How to deploy a Vercel-based application.

### Deploy from your terminal

You can deploy your new Preact project with a single command from your terminal using [Vercel CLI](https://vercel.com/download):

```shell
$ vercel
```

Note that this requires registering on the Vercel site and credentials to be setup locally (so only you can deploy to your site).


### Continous deployment

#### Integration

You can use a Github integration to trigger a deploy when a commit appears on Github.

- https://vercel.com/docs/v2/git-integrations

#### Deploys

See the current and past deploys for this repo:

- https://github.com/MichaelCurrin/preact-now/deployments

Note this is similar to the Environment section used for Github Pages but is separate.

#### URLs

There are many URLs available on a single commit. For example, from [commit](https://github.com/MichaelCurrin/preact-now/commit/a07469a98f0d6d2709a3287c3a3bc28046d0974e#commitcomment-39878578).

- Vercel:
    - https://preact-now-4lexz5ooy.vercel.app
    - https://preact-now.michaelcurrin.vercel.app
    - https://preact-now-git-master.michaelcurrin.vercel.app
- Now
    - https://preact-now-deploy.now.sh
    - https://preact-now.michaelcurrin.now.sh
    - https://preact-now-git-master.michaelcurrin.now.sh
