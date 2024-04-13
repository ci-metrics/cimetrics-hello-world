# cimetrics-hello-world

[![Discord invite link](https://dcbadge.vercel.app/api/server/eYjfCVk3BF)](https://discord.gg/eYjfCVk3BF)

A repo presenting an example system for tracking generic metrics in CI like [codecov](https://about.codecov.io).

![Example PR comment](./example_pr_light.webp#gh-light-mode-only)
![Example PR comment](./example_pr_dark.webp#gh-dark-mode-only)

This is from https://github.com/JonathanWoollett-Light/example/pull/2.

![Example display one](./example_display_light.webp#gh-light-mode-only)
![Example display one](./example_display_dark.webp#gh-dark-mode-only)

This is from https://cimetrics.io/.

## Account setup

1. Go to https://cimetrics.io/
2. Click "Generate login"
3. Store the filled out public key and private key in a password manager.
4. Click "Login"

## Repository setup

1. Copy [pull_request.yml](./.github/workflows/pull_request.yml) and [push.yml](./.github/workflows/push.yml) to your repo.
2. Update `PUBLIC_KEY` and use repository secrets for `PRIVATE_KEY`.

## Help

- [Join the discord](https://discord.gg/eYjfCVk3BF)
- [Post an issue](https://github.com/ci-metrics/example/issues)