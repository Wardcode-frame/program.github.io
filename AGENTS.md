# Agent instructions

This repo is a fork of `JosiahHands/program.github.io`. Cloudflare deploys the live site from `main` in `JosiahHands/program.github.io`, not from this fork.

## Pull requests

When you edit this repo and are asked to "make a pull request", open it from this fork into `JosiahHands/program.github.io`, with base `main`:

```sh
gh pr create -R JosiahHands/program.github.io --base main --head Wardcode-frame:<branch>
```

Do not merge it. The owner reviews and merges every pull request.
