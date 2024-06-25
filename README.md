# pterodactyl-fivem

## feature plans 
I do plan on supporting [pelican](https://pelican.dev) and [pterodactyl](https://pterodactyl.io) at the same time when pelican first stable release comes out there will be two eggs to support this :)

## About
This is a script to install FiveM on a Debian 12 server. It will install the latest version of FiveM and automatically keep it updated. It will also install the latest version of FXServer.

## Installation
1. Download the egg from the [Releases](https://github.com/Luxxy-GF/pterodactyl-fivem/releases/latest) 
2. Upload the egg to your panel
3. Create a new server and select the FiveM egg
4. Start the server and wait for it to install
5. Once the server is started, stop it
## Updating
1. Go to the `Startup` tab
2. Change the `Auto Update` to the desired value (default: `1` | `0` = disabled, `1` = enabled) note: this will delete `alpine` folder and reinstall it `no data will be lost`

## Notice

The `FIVEM_VERSION` variable.

* Defaults to `latest` which is the latest optional artifact.
* Can be set to a specific version Ex. `7549-801114291131277b01c25158b4261df6efbbc610`.
* If the `Auto Update` Button is turned on when you press th `Reinstall Server` button the `alpine` folder will be replaced with an updated version.

## Server Ports

Ports required to run the server in a table format. You only need the txAdmin port if you plan to enable txAdmin.

| Port | default |
| - | - |
| FiveM | 30120 |
| txAdmin | 40120 |

## Credits
- [Luxxy-GF](https://github.com/Luxxy-GF) - Creator of the egg
- [Pterodactyl](https://pterodactyl.io) - Panel used
- [FiveM](https://fivem.net) - Game server software used
- [parkervcp](https://github.com/parkervcp) - Creator of the original egg

## Support
If you need help with this egg, you can create a issue on this repo

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## pull request
if you want to help me with this egg you can create a pull request
