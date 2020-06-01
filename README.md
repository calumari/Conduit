# Conduit
Fork of [Paper](https://github.com/PaperMC/Paper) used by the Social Hangover network.

Use at your own risk. Conduit contains patches suited to our needs. No support will be given.

## License
See [electronicboy/byof](https://github.com/electronicboy/byof), [starlis/empirecraft](https://github.com/starlis/empirecraft), [Spottedleaf/Tuinity](https://github.com/Spottedleaf/Tuinity) and [pl3xgaming/Purpur](https://github.com/pl3xgaming/Purpur) for the license of material used/modified by this project.

## Building
Run the following commands in the root directory:
```
git submodule update --init
./conduit up
./conduit patch
```
If all you want is a paperclip server jar, run `./conduit jar`.

Otherwise, use `./conduit build` to build the respective api and server jars.
#### Creating a patch
See [Paper's contributing guideline](https://github.com/PaperMC/Paper/blob/master/CONTRIBUTING.md) for more information.