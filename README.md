```json
{
  "inbounds": [
    {
      "port": 1086,
      "protocol": "socks",
      "sniffing": {
        "enabled": true,
        "destOverride": ["http", "tls"]
      },
      "settings": {
        "auth": "noauth"
      }
    }
  ],
  "outbounds": [
    {
      "protocol": "vmess",
      "settings": {
        "vnext": [
          {
            "address": "35.236.174.166",
            "port": 18230,
            "users": [
              {
                "id": "5f605c67-cc13-44ac-89fe-b525a5cea12b",
                "alterId": 64
              }
            ]
          }
        ]
      }
    }
  ]
}
