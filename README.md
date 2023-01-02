# getwall

Browser [wallhaven](https://wallhaven.cc/) using `sxiv`

## Usage
```
getwall <query>
```
> Leave query empty to use `dmenu`

- Select wallpapers by marking them using `m` in `sxiv`.
- Quit `sxiv` using `q`.

Selected images would be downloaded. The default download directory is

	~/Wallpapers

Defaults can be changed by changing the user variables, in the start of the
script.


## Dependencies

* sxiv
* jq
* curl
* dmenu / rofi ( *optional* )
