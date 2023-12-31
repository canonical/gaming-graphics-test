# gaming-graphics-test

Simple snap for glxgears, vkcube, glxinfo, and vulkaninfo utilizing the [gaming-graphics-core22 content snap][gaminggraphics].

Based largely on the [Steam snap](https://github.com/canonical/steam-snap).

## Using gaming-graphics-test

Run the applications with

```
snap run gaming-graphics-test.glxgears
snap run gaming-graphics-test.glxinfo
snap run gaming-graphics-test.vkcube
snap run gaming-graphics-test.vulkaninfo
```

Or, run the apps via their .desktop files in your application launcher.

## Using [gaming-graphics-core22][gaminggraphics]

### Connect

Connect gaming-graphics-core22 to the gaming-graphics-test snap with

```
snap connect gaming-graphics-test:gaming-mesa gaming-graphics-core22
```

### Switch Channels

Switch gaming-graphics-core22 channels with

```
snap refresh gaming-graphics-core22 --channel <channel>
# replace <channel> with kisak-turtle, kisak-fresh, or oibaf-latest
```



[gaminggraphics]: https://github.com/canonical/gaming-graphics/
