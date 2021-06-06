# Usage

## geosite

```json
"routing": {
  "domainMatcher": "mph",
  "domainStrategy": "AsIs",
  "rules": [
    {
      "type": "field",
      "outboundTag": "direct",
      "domains": [
        "ext:dlc.dat:china",
      ]
    }
  ]
}
```

<table>
  <thead>
    <tr>
      <th>Category</th>
      <th>Format</th>
      <th>URL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" rowspan="2">All-in-One</td>
      <td align="center" rowspan="2">GEOSITE</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/geosite/dlc.dat
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@geosite/dlc.dat
      </td>
    </tr>
  </tbody>
</table>

## mihomo

```yaml
rule-providers:
  CHINA:
    behavior: domain
    type: http
    url: "https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/china.mrs"
    path: ./china.mrs
    format: mrs
    interval: 86400
rules:
  - RULE-SET,CHINA,DIRECT
```

<table>
  <thead>
    <tr>
      <th>Category</th>
      <th>Format</th>
      <th>URL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" rowspan="4">Apple</td>
      <td align="center" rowspan="2">MRS</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/mihomo/apple.mrs
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/apple.mrs
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="2">YAML</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/mihomo/apple.yaml
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/apple.yaml
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="4">China</td>
      <td align="center" rowspan="2">MRS</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/mihomo/china.mrs
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/china.mrs
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="2">YAML</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/mihomo/china.yaml
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/china.yaml
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="4">Google</td>
      <td align="center" rowspan="2">MRS</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/mihomo/google.mrs
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/google.mrs
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="2">YAML</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/mihomo/google.yaml
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@mihomo/google.yaml
      </td>
    </tr>
  </tbody>
</table>

## sing-box

```json
"route": {
  "rules": [
    {
      "outbound": "direct",
      "rule_set": ["china"],
    }
  ],
  "rule_set": [
    {
      "type": "remote",
      "tag": "china",
      "format": "binary",
      "url": "https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/china.srs"
    }
  ]
}
```

<table>
  <thead>
    <tr>
      <th>Category</th>
      <th>Format</th>
      <th>URL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" rowspan="4">Apple</td>
      <td align="center" rowspan="2">SRS</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/sing-box/apple.srs
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/apple.srs
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="2">JSON</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/sing-box/apple.json
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/apple.json
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="4">China</td>
      <td align="center" rowspan="2">SRS</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/sing-box/china.srs
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/china.srs
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="2">JSON</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/sing-box/china.json
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/china.json
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="4">Google</td>
      <td align="center" rowspan="2">SRS</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/sing-box/google.srs
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/google.srs
      </td>
    </tr>
    <tr>
      <td align="center" rowspan="2">JSON</td>
      <td>
        https://raw.githubusercontent.com/akiirui/domain-list-china/sing-box/google.json
      </td>
    </tr>
    <tr>
      <td>
        https://cdn.jsdelivr.net/gh/akiirui/domain-list-china@sing-box/google.json
      </td>
    </tr>
  </tbody>
</table>
