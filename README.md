# QuickShop-OG WorldEdit Compatibility

GPLv3 compatibility extension for QuickShop-OG and WorldEdit.

The extension observes WorldEdit operations and removes a QuickShop-OG record when the corresponding shop block is removed. This prevents orphaned or ghost shops after administrative edits.

## Requirements

- Java 17
- QuickShop-OG, based on the 5.2.0.7 API
- WorldEdit 7.2.17 or a compatible release

## Build

Run `./gradlew build` from this repository. The resulting plugin JAR is `build/libs/QuickShop-OG-compat-worldedit-5.9.jar`.

## Install

Place the built JAR in the server's `plugins/` directory beside `QuickShop-OG.jar` and the WorldEdit JAR. Restart the server; do not place this JAR in `plugins/QuickShop-OG/`.

## License

GPL-3.0-only. See [LICENSE](LICENSE).
