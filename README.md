# pipeline

Build Tor Browser and Tor using GitHub Actions.

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

