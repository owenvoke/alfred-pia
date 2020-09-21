# Alfred PIA

[![Latest Version on GitHub][ico-version]][link-releases]
[![Software License][ico-license]](LICENSE.md)

Manage Private Internet Access in Alfred using "piactl"

## Install

Via Alfred

Download the Alfred file from the [Releases](https://github.com/owenvoke/alfred-pia/releases).

## Usage

This workflow provides a few commands for managing Private Internet Access.

| Command                   | Description                                                                                        |
| ------------------------- | -------------------------------------------------------------------------------------------------- |
| `pia connect`             | Connect to the configured Private Internet Access region.                                          |
| `pia disconnect`          | Disconnect from the current Private Internet Access endpoint.                                      |
| `pia region [region]`     | Set the configured region for Private Internet Access (use "auto" for automatic region selection). |
| `pia protocol [protocol]` | Set the PIA protocol to either "openvpn" or "wireguard". Default is OpenVPN.                       |
| `pia background`          | Start PIA in the background so that the GUI doesn't need to be running.                            |
| `pia exit`                | Stop the background daemon if it is running.                                                       |

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email security@voke.dev instead of using the issue tracker.

## Credits

- [Owen Voke][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## Treeware

You're free to use this package, but if it makes it to your production environment you are required to buy the world a tree.

It’s now common knowledge that one of the best tools to tackle the climate crisis and keep our temperatures from rising above 1.5C is to plant trees. If you support this package and contribute to the Treeware forest you’ll be creating employment for local families and restoring wildlife habitats.

You can buy trees [here][link-treeware-gifting].

Read more about Treeware at [treeware.earth][link-treeware].

[ico-version]: https://img.shields.io/github/v/tag/owenvoke/alfred-pia.svg?sort=semver&style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square

[link-releases]: https://github.com/owenvoke/alfred-pia/releases
[link-treeware]: https://treeware.earth
[link-treeware-gifting]: https://ecologi.com/owenvoke?gift-trees
[link-author]: https://github.com/owenvoke
[link-contributors]: ../../contributors
