The ViaVersion suite allows server owners as well as players to allow client connection to servers of different
Minecraft versions through a bit of magic:tm:. Below, you can find an overview of the projects to find the one that
suits your exact needs.

## Paper (and other Spigot forks), Velocity, Bungee, Sponge plugins

|                     | [ViaVersion](https://github.com/ViaVersion/ViaVersion)       | [ViaBackwards](https://github.com/ViaVersion/ViaBackwards) (requires ViaVersion) | [ViaRewind](https://github.com/ViaVersion/ViaRewind) (requires ViaVersion)                                       |
|---------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| Installed on        | Server: 1.8.8-latest                                         | Servers: 1.10-latest                                                             | Servers: 1.8.8-latest                                                                                            |
| Allows              | All client versions that are **newer than your server**      | Client versions that are **older than your server** down to 1.9                  | 1.7.10-1.8.9 clients                                                                                             |
| Additional benefits | Less gameplay and anti-cheat issues if run on a Paper server |                                                                                  | Less gameplay issues if using [ViaRewind Legacy Support](https://github.com/ViaVersion/ViaRewind-Legacy-Support) |

## Fabric, Forge mods

Depending on the setup, these include ViaVersion, ViaBackwards, ViaRewind, and ViaLegacy.

|                     | [ViaFabric](https://github.com/ViaVersion/ViaFabric)                                                                                                                    | [ViaFabricPlus](https://github.com/ViaVersion/ViaFabricPlus) | [ViaForge](https://github.com/ViaVersion/ViaForge) |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------|
| Installed on        | Fabric client or server: Latest minor version of 1.8, 1.14-latest                                                                                                       | Fabric client: Latest                                        | Forge client: 1.8.8, 1.12.2                        |
| Allows              | Connecting to 1.8.8-latest servers*                                                                                                                                     | Connecting to classic c0.0.15 to latest release servers      | Connecting to 1.8.8-latest servers                 |
| Additional benefits | Less potential for mod incompatibilities than ViaFabricPlus. You can also replace the bundled ViaVersion by placing a newer/custom ViaVersion jar in the mods directory | Less gameplay and anti-cheat issues                          |                                                    |

*If you want to connect to servers that are newer than your client, you need to add ViaBackwards (and ViaRewind on 1.8)
to your mod directory.

## Standalone proxies

These are proxies you host. By connecting through them with your client (can be modded or unmodded), you can join
servers of different versions. Depending on the setup, these include ViaVersion, ViaBackwards, ViaRewind, and ViaLegacy.

|                     | [ViaAAS](https://github.com/ViaVersion/VIAaaS)                                                              | [ViaProxy](https://github.com/ViaVersion/ViaProxy)                      |
|---------------------|-------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| Installed on        | Local or remote instances to any server                                                                     | Local instances to any server, or remote instances to a specific server |
| Allows              | Connecting to 1.8.8-latest servers                                                                          | Connecting to classic c0.0.15-latest servers                            |
| Additional benefits | Has already running, [public instances](https://github.com/ViaVersion/VIAaaS/wiki/List-of-Public-Instances) | User-friendly graphical user interface for local instances              |
