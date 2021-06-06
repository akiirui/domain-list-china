# domain-list-china

Domain list based on [felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list), Generator by [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) tools.

## Usage

```json
{
  "routing": {
    "domainStrategy": "AsIs",
    "rules": [
      {
        "type": "field",
        "outboundTag": "direct",
        "domain": [
          "ext:dlc.dat:china",
          "ext:dlc.dat:apple",
          "ext:dlc.dat:google"
        ]
      }
    ]
  }
}
```

## Install

- Arch Linux: [v2ray-domain-list-china](https://aur.archlinux.org/packages/v2ray-domain-list-china/) <sup>AUR</sup>

## Thanks

- [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- [felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
