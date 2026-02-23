# elementary Fonts

Default fonts that we rely on in elementary OS

## License

"Redacted" is available under SIL OPEN FONT LICENSE Version 1.1

"Roboto Mono" is available under Apache License Version 2

## Crosscore

We ship a fontconfig file that maps metrically compatible open-source fonts Arimo (sans-serif), Tinos (serif) and Cousine (monospace) to Arial, Times New Roman, and Courier New, respectively.

## Installation

You'll need the following dependencies:
* meson

Run `meson setup` to configure the build environment

```bash
    meson setup build --prefix=/usr
```

Change to the build directory and run `ninja install` to install

```bash
    cd build
    ninja install
```
