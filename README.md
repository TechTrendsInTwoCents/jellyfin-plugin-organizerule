# Jellyfin OrganizeRule Plugin

Forked from [jellyfin/jellyfin-plugin-autoorganize](https://github.com/jellyfin/jellyfin-plugin-autoorganize), built with `netstandard2.1`
</p>

## Build Process

1. Clone or download this repository
2. Ensure you have .NET Core SDK setup and installed
3. Build plugin with following command.
    ```sh
    dotnet publish --configuration Release --output bin
    ```
4. Place the resulting `TwoCents.JellyfinOrganizeRule.dll` file in a folder called `plugins/` under the program data directory or inside the portable install directory, service restart is required.