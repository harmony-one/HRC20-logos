# HRC20-logos
Repository to store HRC20 token logos
* The HRC20 token logos will be used by several clients such as Harmony block explorer when displaying the infomations of HRC20.


## Steps to add your HRC20 logo
* Fork this repository
* Add your logo by creating the logo image name using your HRC20 contract one-address and placing it inside `HRC20/`, e.g. `HRC20/one1pdv9lrdwl0rg5vglh4xtyrv3wjk3wsqket7zxy.png`
* Append your HRC20 token's basic information (including address, name, symbol, decimals, totalSupply, description, website) to the bottom of the list.json,

For example, append yours to the last lines of [list.json](https://github.com/harmony-one/HRC20-logos/blob/master/list.json)

```
[
...
{
    "address": "one10y76c0kyj6d9hmngf0859yx49l4c75d5z77zxr",
    "name": "SEED",
    "symbol": "SEED",
    "decimals": 6,
    "totalSupply": "201925001200",
    "website": "https://harmony.one",
    "description": {
        "en": "..."
    }
}
]
```

* Create a PR
* Once the Harmony team approves your logo, it will be consumed by clients like Harmony block explorer


## Image Requirements
- dimension: `256px by 256px` or `512px by 512px`
- size: up to `100 KB`. TIP: use free drag and drop online service [tinypng](https://tinypng.com/) to optimize image size
