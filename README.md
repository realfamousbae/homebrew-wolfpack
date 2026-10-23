# Homebrew tap of wolfpack

[wolfpack](https://github.com/realfamousbae/wolfpack) is a statically typed language whose
compiler, `wolf`, translates programs into readable TypeScript, Go and Rust.

```bash
brew install realfamousbae/wolfpack/wolfpack
```

`brew upgrade wolfpack` updates it. `wolf run --vm` runs programs without other tools; `wolf setup`
installs Node.js, TypeScript, Go and Rust for the targets.

`Formula/wolfpack.rb` is written by `release/homebrew/formula.sh` of the wolfpack repository: its
workflow `packages.yml` updates it when a release is published. Change the script there, not the
formula here.
