# QMK layouts for planck

Collection of various layouts for my planck

## Compile and Flash on linux

Make sure to have qmk installed

```bash
$ qmk setup
```

Compile the layout using [QMK Configurator](https://config.qmk.fm) or using the command

```bash
$ qmk compile -c <filename>.json
```

Make sure that the keyboard is pluggen in DFU Mode and run

```bash
$ qmk flash -m atmega32u4 <filename>.bin
```