# @del-wang/config

## 1.8.0

### Minor Changes

- fix(biome): migrate to `nursery.useTailwindSortedClasses`

  Biome v2.6 renamed `nursery.useSortedClasses` to `nursery.useTailwindSortedClasses` and moved its `attributes` / `functions` options to the top-level `tailwind` configuration. The old key is now rejected as an unknown key, which makes Biome fail to load the whole config (breaking format-on-save in the VS Code extension and the `biome` CLI).

  This preset now requires Biome v2.6+.

## 1.7.0

### Minor Changes

- fix: tsconfig path

## 1.6.0

### Minor Changes

- chore: bump deps

## 1.5.0

### Minor Changes

- refactor: migrate to tsdown

## 1.4.0

### Minor Changes

- feat: add nextjs config and none symbol

## 1.3.0

### Minor Changes

- 5f0892a: feat: add more logger and time utils

### Patch Changes

- cea9035: chore: add tsx file entry for tsup

## 1.2.0

### Minor Changes

- b4e1083: chore: node >= 18

## 1.1.0

### Minor Changes

- c9bd943: chore: use relative path for config file schema
