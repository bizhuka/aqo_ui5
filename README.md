### ABAP quick options (ui5 version) 

Last compatible version of main package is
https://github.com/bizhuka/aqo/tree/last-version-2.0

obsolete from 27.10.2021

### Add-in for [aqo](https://github.com/bizhuka/aqo)

## The installation process is tricky, sometimes it's better to launch SE38 -> BSP_UPDATE_MIMEREPOS or ZAQO_LOADER to upload BSP application MIMEs objects

## Before installation add the following item to SDOKMIME! (also delete previous BSP application in the package, otherwise various errors occur)

| EXTENSION        | TYPE           | 
| ------------- |:-------------:|
| json    | application/json |
