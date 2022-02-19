# Tor for Actions

This repository contains the code and scripts that we use to build Tor binaries used in [virtual-environments](https://github.com/actions/virtual-environments) and accessible through the [setup-tor](https://github.com/tor-actions/setup-tor) Action.

File [versions-manifest.json](./versions-manifest.json) contains the list of available and released versions.

> Caution: this is prepared for and only permitted for use by actions `virtual-environments` and `setup-tor` action.

## Binaries path structure

### Linux

```
./tor-linux-0.4.5.7/
|-- bin
|   |-- tor
|   |-- tor-gencert
|   |-- tor-print-ed-signing-cert
|   |-- tor-resolve
|   `-- torify
|-- etc
|   `-- tor
|       `-- torrc.sample
`-- share
    `-- tor
        |-- geoip
        `-- geoip6
```

### macOS

```
./tor-darwin-amd64-0.4.5.7/
|-- bin
|   |-- tor
|   |-- tor-gencert
|   |-- tor-print-ed-signing-cert
|   |-- tor-resolve
|   `-- torify
|-- etc
|   `-- tor
|       `-- torrc.sample
`-- share
    `-- tor
        |-- geoip
        `-- geoip6
```

### Windows

```
./tor-win32-0.4.5.7/
|-- bin
|   |-- tor-gencert.exe
|   |-- tor-print-ed-signing-cert.exe
|   |-- tor-resolve.exe
|   |-- tor.exe
|   `-- torify
|-- etc
|   `-- tor
|       `-- torrc.sample
`-- share
    `-- tor
        |-- geoip
        `-- geoip6
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

