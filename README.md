<h1 align="center">Metadata Query Logger Plugin</h1>

<p align="center">
<img alt="Plugin Banner" src="https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/plugins/SVG/jellyfin-plugin-playbackreporting.svg?sanitize=true"/>
<br/>
<br/>
<a href="https://github.com/thedreaddpirate/metadata-query-logger/actions?query=workflow%3A%22Test+Build+Plugin%22">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/thedreaddpirate/metadata-query-logger/Test%20Build%20Plugin.svg">
</a>
<a href="https://github.com/thedreaddpirate/metadata-query-logger">
<img alt="GPLv3 License" src="https://img.shields.io/github/license/jellyfin/jellyfin-plugin-playbackreporting.svg"/>
</a>
<a href="https://github.com/thedreaddpirate/metadata-query-logger/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin-plugin-playbackreporting.svg"/>
</a>
</p>

## About

WIP - A plugin that will log metadata queries for troubleshooting purposes.

## Installation

## Build

1. To build this plugin you will need [.Net 10.x](https://dotnet.microsoft.com/download/dotnet/10.0).

2. Build plugin with following command
  ```
  dotnet publish --configuration Release --output bin
  ```

3. Place the dll-file in the `plugins/metadataquerylogger` folder (you might need to create the folders) of your JF install

## Releasing

To release the plugin we recommend [JPRM](https://github.com/oddstr13/jellyfin-plugin-repository-manager) that will build and package the plugin.
For additional context and for how to add the packaged plugin zip to a plugin manifest see the [JPRM documentation](https://github.com/oddstr13/jellyfin-plugin-repository-manager) for more info.

## Contributing

We welcome all contributions and pull requests! If you have a larger feature in mind please open an issue so we can discuss the implementation before you start.
In general refer to our [contributing guidelines](https://github.com/jellyfin/.github/blob/master/CONTRIBUTING.md) for further information.

## Licence

This plugins code and packages are distributed under the GPLv3 License. See [LICENSE](./LICENSE) for more information.
