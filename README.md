# base-package-mycelium

The repository layer: layered git repositories (mycelium-git, -layer, -repo), topics, URIs and paths; with p2p-git, git on Hyperdrive, which mycelium-git runs on.

A package: self-contained, its code ready to run, laid out as it is installed. Written by the package manager (`pear-full-square/pkgm-base-manager`) from the development repository; do not edit here.

- requires: `haiccing/base-package-third-party`
- hash: `4967f2d428f2a2e303cf8264087eb7bab348e95eac4796858487eeac93b07812`

## Holds

- `pear-full-square/mycelium-uri`
- `pear-full-square/mycelium-xpath`
- `pear-full-square/mycelium-topic`
- `pear-full-square/mycelium-git`
- `pear-full-square/mycelium-layer`
- `pear-full-square/mycelium-repo`
- `pear-full-square/p2p-git`

## Installed

By the package manager, into the host's install folder (`~/.haicc/packages`), with the packages it requires; its tests run there:

```sh
node <install folder>/pear-full-square/pkgm-base-manager/cli.js install mycelium --from <folder of haiccing repositories>
node <install folder>/pear-full-square/pkgm-base-manager/cli.js test mycelium
```
