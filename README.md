# v2ray_http_json
JSON file for v2ray with http proxy

```json
"inbounds": [
	{
	"protocol": "http",
	"listen": "0.0.0.0",
	"settings": {
	 	"timeout": 0,
		"accounts": [
			{
		 	"user": "username",
		 	"pass": "password"
			}
		],
	"allowTransparent": false,
	"userLevel": 0
	},
	"port": 2080,
	"streamSettings": null}
	]
	}
```
