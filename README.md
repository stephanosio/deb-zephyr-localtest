### Steps

1. Generate source package
    ```
    git-build-recipe --allow-fallback-to-native zephyr-crosstool-aarch64.recipe build
    ```

2. Build for a distro
    ```
    pbuilder-dist bionic amd64 build build/zephyr-crosstool-aarch64_*.dsc
    ```
