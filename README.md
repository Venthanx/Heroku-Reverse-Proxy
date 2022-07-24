# Heroku Reverse Proxy with Caddy
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

```
快速指令

git add * 
git commit -m "make it better" 
git push heroku main 
heroku ps:scale web=1
heroku open

```

```
	"env": {
		"UPSTREAM": {
			"description": "Upstream URL ( 请带上 http/s & 结尾无需 '/' )",
			"value": ""
		},
		"PORT": {
			"description": "端口号",
			"value": ""
		}
	}
```