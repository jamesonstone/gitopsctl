# gitopsctl

A Github Actions for handling CD configurations with [Flux](https://fluxcd.io/)

## Overview

gitopsctl maintains CD with Flux by building images based on their stated versions and push to the registry. It also takes care to do manual updates to the GitOps repository to ensure Deployments are version appropriately.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: jstone28/gitopsctl
with:
  who-to-greet: 'Mona the Octocat'
