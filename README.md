# pipeline

Build Tor Browser and Tor using GitHub Actions.

## Binaries path structure

### Linux

```
./tor-0.4.5.7-linux
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

*WIP*

### Windows

```
./tor-0.4.5.7-win32/
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

