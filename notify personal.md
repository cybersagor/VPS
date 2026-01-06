### Test Command
```
echo "Test" | notify -provider discord -id spider -silent
```


### Command
```
mkdir $HOME/.config/notify/
nano $HOME/.config/notify/provider-config.yaml
```

### Config File

```
discord:
  - id: "nuclearone"
    discord_channel: "nuclearone"
    discord_username: "Scanner"
    discord_format: "{{data}}"
    discord_webhook_url: "https://discord.com/api/webhooks/1349159216660611094/n4JYLe3aOpP0esAQQ6W3lxsrAfM1UGcnKKb3fHC7ztxWSiFV_dIqoKaIr3pPwWRvmAqi"

  - id: "httput"
    discord_channel: "httput"
    discord_username: "HTTPut"
    discord_format: "{{data}}"
    discord_webhook_url: "https://discord.com/api/webhooks/1340501922360201216/-gDR1G4jSG71vdY8UX-ITq_dY8sBW4SGFmrQw8vv2tYJcC85UTpedV8uaOCgq4CuHyN2"

  - id: "spider"
    discord_channel: "spider"
    discord_username: "Spider"
    discord_format: "{{data}}"
    discord_webhook_url: "https://discord.com/api/webhooks/1437512883486330941/QfaRHMgdsEZz093ecw74Jb7a6o2-is7yAnPi7PiBJIrMrR2xp_Yw-QnyBzVJQcq5cVzM"

  - id: "miner"
    discord_channel: "miner"
    discord_username: "Miner"
    discord_format: "{{data}}"
    discord_webhook_url: "https://discord.com/api/webhooks/1455109217806581770/6zVMJ9UOoEGEUm-CEd7YxZkpwv-MkqXsXYF6UDSSvbIoFOkMpNuGh_06dmXmidT4Q-zG"

  - id: "httpx"
    discord_channel: "httpx"
    discord_username: "HTTPx"
    discord_format: "{{data}}"
    discord_webhook_url: "https://discord.com/api/webhooks/1455109557679427689/UxQvDbFiVvMFzRRet69kDI7RfHJlqGn4jLoMTApjhPJ19fQyANs2xA5xRw5xcgCqE6Fl"

  - id: "yogosha"
    discord_channel: "yogosha"
    discord_username: "yogoshaNT"
    discord_format: "{{data}}"
    discord_webhook_url: "https://discord.com/api/webhooks/1455109001145483366/uNxw6CCNluWoo1exLl6YSF4CAGGB_smkI_fB6x9fn5TswRH1noboQVdovfWcxDA9hds6"
```
