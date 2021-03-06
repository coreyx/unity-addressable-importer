<p align="center">
  <img width="180" src="https://raw.githubusercontent.com/favoyang/unity-addressable-importer/master/Media/icon-512.png" alt="logo">
</p>
<h1 align="center">Unity Addressable Importer</h1>
<p align="center">
  <a href="https://openupm.com/packages/com.littlebigfun.addressable-importer/">
    <img src="https://img.shields.io/npm/v/com.littlebigfun.addressable-importer?label=openupm&amp;registry_uri=https://package.openupm.com" />
  </a>
  <a href="#contributors">
    <img src="https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square"/>
  </a>
</p>

A simple rule based addressable asset importer. The importer marks assets as addressable, by applying to files having a path matching the rule pattern.

Table of Contents

- [Install Package](#install-package)
  - [Install via OpenUPM](#install-via-openupm)
  - [Install via Git URL](#install-via-git-url)
- [How to Use](#how-to-use)
- [Contributors ✨](#contributors-)
- [Media](#media)

## Install Package

### Install via OpenUPM

The package is available on the [openupm registry](https://openupm.com). It's recommended to install it via [openupm-cli](https://github.com/openupm/openupm-cli).

```
openupm add com.littlebigfun.addressable-importer
```

### Install via Git URL

Open *Packages/manifest.json* with your favorite text editor. Add the following line to the dependencies block.

    {
        "dependencies": {
            "com.littlebigfun.addressable-importer": "https://github.com/favoyang/unity-addressable-importer.git"
        }
    }

Notice: Unity Package Manager records the current commit to a lock entry of the *manifest.json*. To update to the latest version, change the hash value manually or remove the lock entry to resolve the package.

    "lock": {
      "com.littlebigfun.addressable-importer": {
        "revision": "master",
        "hash": "..."
      }
    }

## How to Use

See [usage](./Documentation~/AddressableImporter.md)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="http://littlebigfun.com"><img src="https://avatars2.githubusercontent.com/u/125390?v=4" width="100px;" alt="Favo Yang"/><br /><sub><b>Favo Yang</b></sub></a><br /><a href="https://github.com/favoyang/unity-addressable-importer/commits?author=favoyang" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AlkisFortuneFish"><img src="https://avatars2.githubusercontent.com/u/43749706?v=4" width="100px;" alt="AlkisFortuneFish"/><br /><sub><b>AlkisFortuneFish</b></sub></a><br /><a href="https://github.com/favoyang/unity-addressable-importer/commits?author=AlkisFortuneFish" title="Code">💻</a></td>
    <td align="center"><a href="http://www.insanegames.com.br"><img src="https://avatars0.githubusercontent.com/u/2972924?v=4" width="100px;" alt="Danilo Nishimura"/><br /><sub><b>Danilo Nishimura</b></sub></a><br /><a href="https://github.com/favoyang/unity-addressable-importer/commits?author=danilonishi" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/K-Dark"><img src="https://avatars2.githubusercontent.com/u/44504098?v=4" width="100px;" alt="K-Dark"/><br /><sub><b>K-Dark</b></sub></a><br /><a href="https://github.com/favoyang/unity-addressable-importer/commits?author=K-Dark" title="Code">💻</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## Media

Icons made by [Freepik](https://www.flaticon.com/authors/freepik) from [flaticon.com](http://www.flaticon.com)
