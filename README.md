![test](https://github.com/thundermiracle/.github/workflows/test/badge.svg)

## .github

This repository contains the basic Renovate configuration that is used in all other thundermiracle repositories.

## Usage

Create file `renovate.json` in the root of the repository.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "description": "Onboarding preset for use with ThunderMiracle's repos",
  "extends": ["github>thundermiracle/.github"]
}
```
