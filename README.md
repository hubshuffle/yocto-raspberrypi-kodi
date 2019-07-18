# Compiling Yocto with Kodi for the Raspberry Pi (3B+)

## How To

Initialise the sub-modules:
```bash
git  submodule update --init
```
You might need to add *warrior* to the list of compatible layers of *meta-kodi*.

Next up is the usual poky build commands and I made an example image recipe which is named *example-image*, yeah, I know..

```bash
bitbake example-image
```

