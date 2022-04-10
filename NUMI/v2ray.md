白名单
```json
[
  {
    "type": "field",
    "inboundTag": [],
    "outboundTag": "block",
    "domain": [
      "geosite:category-ads-all"
    ],
    "enabled": true
  },
  {
    "type": "field",
    "inboundTag": [],
    "outboundTag": "direct",
    "domain": [
      "geosite:apple-cn",
      "geosite:category-games@cn",
      "geosite:google-cn",
      "geosite:private",
      "geosite:tld-cn"
    ],
    "enabled": true
  },
  {
    "type": "field",
    "inboundTag": [],
    "outboundTag": "proxy",
    "domain": [
      "geosite:geolocation-!cn"
    ],
    "enabled": true
  },
  {
    "type": "field",
    "inboundTag": [],
    "outboundTag": "direct",
    "domain": [
      "geosite:cn"
    ],
    "enabled": true
  },
  {
    "type": "field",
    "inboundTag": [],
    "outboundTag": "direct",
    "ip": [
      "114.114.114.114/32",
      "119.29.29.29/32",
      "180.76.76.76/32",
      "223.5.5.5/32",
      "geoip:cn",
      "geoip:private"
    ],
    "enabled": true
  },
  {
    "type": "field",
    "inboundTag": [],
    "outboundTag": "proxy",
    "ip": [
      "1.0.0.1/32",
      "1.1.1.1/32",
      "8.8.4.4/32",
      "8.8.8.8/32",
      "geoip:ca",
      "geoip:telegram",
      "geoip:us"
    ],
    "enabled": true
  },
  {
    "port": "0-65535",
    "outboundTag": "proxy",
    "enabled": true
  }
]
```

黑名单
```json
[
  {
    "type": "field",
    "port": "",
    "inboundTag": [],
    "outboundTag": "block",
    "ip": [],
    "domain": [
      "geosite:category-ads-all"
    ],
    "protocol": [],
    "enabled": true
  },
  {
    "type": "field",
    "port": "",
    "inboundTag": [],
    "outboundTag": "proxy",
    "ip": [],
    "domain": [
      "geosite:gfw",
      "geosite:greatfire"
    ],
    "protocol": [],
    "enabled": true
  },
  {
    "type": "field",
    "port": "",
    "inboundTag": [],
    "outboundTag": "proxy",
    "ip": [
      "geoip:telegram"
    ],
    "domain": [],
    "protocol": [],
    "enabled": true
  },
  {
    "type": "field",
    "port": "",
    "inboundTag": [],
    "outboundTag": "direct",
    "ip": [
      "114.114.114.114/32",
      "119.29.29.29/32",
      "180.76.76.76/32",
      "223.5.5.5/32",
      "geoip:cn",
      "geoip:private"
    ],
    "domain": [],
    "protocol": [],
    "enabled": true
  },
  {
    "type": "field",
    "port": "",
    "inboundTag": [],
    "outboundTag": "proxy",
    "ip": [
      "1.0.0.1/32",
      "1.1.1.1/32",
      "8.8.4.4/32",
      "8.8.8.8/32",
      "geoip:ca",
      "geoip:telegram",
      "geoip:us"
    ],
    "domain": [],
    "protocol": [],
    "enabled": true
  },
  {
    "port": "0-65535",
    "outboundTag": "proxy",
    "enabled": true
  }
]
```