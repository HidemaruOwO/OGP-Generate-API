<div align="center">

![Last commit](https://img.shields.io/github/last-commit/HidemaruOwO/ogp-generate-api?style=flat-square)
![Repository Stars](https://img.shields.io/github/stars/HidemaruOwO/ogp-generate-api?style=flat-square)
![Issues](https://img.shields.io/github/issues/HidemaruOwO/ogp-generate-api?style=flat-square)
![Open Issues](https://img.shields.io/github/issues-raw/HidemaruOwO/ogp-generate-api?style=flat-square)
![Bug Issues](https://img.shields.io/github/issues/HidemaruOwO/ogp-generate-api/bug?style=flat-square)

# OGP Create ð

v1.0-beta2

## ãªãã ããã¯

ãã® API ã«ä»»æã®ãã­ã¹ããå«ãã¦ POST ãããã¨ããã®ãã­ã¹ããåãè¾¼ãã ãµã¤ãç¨ã® OGP ãçæãã¾ãã

</div>

## ð ä½¿ãæ¹

### ãªãã¸ããªã®ã¯ã­ã¼ã³

```bash
git clone https://github.com/HidemaruOwO/OGP-Create
cd ogp-create
```

### ð¨ ãã«ã

```bash
go build src/ogc.go
```

### ð¨ å®è¡

CORS å¯¾å¿ã®ããã`--page-domain`åã³`--api-domain`ãã©ã°ãå¿è¦ã§ãã  
ããããã®ã¢ããªãå®è¡ããã¦ãããµã¼ãã¼ã«ç´ã¥ãããããã¡ã¤ã³ã `api.ogc.v-sli.me` ã§ãPOST ããããã®ãã¼ã¸ã®ãã¡ã¤ã³ã `ogc.v-sli.me`ã®å ´åã¯ä»¥ä¸ã®ã³ãã³ãã®ããã«ãªãã¾ãã  
é æ¬¡ãªãã·ã§ã³ã®å¤ãå¤æ´ãã¦ãã ããã  
Local ã§å®çµããããå ´åã¯å¤ã¯ãå¥½ããªå¤ãå¥ãã¦ãã ããã

```bash
./ogc --api-domain api.ogc.v-sli.me --page-domain ogc.v-sli.me
```

ããã§ãµã¼ãã¼ãèµ·åãã¾ãã  
è©¦ãã«ä½ããã POST ãã¦ã¿ã¦ãã ããã

```bash
curl -X POST -H "Content-Type: application/json" -d '{"text" : "ããã¯ãã¹ãã§ã"}' http://127.0.0.1:3090/generate
```

### â ãã«ã

```
Usage:
   [flags]

Flags:
  -a, --api-domain string    API Domain option (Example: api.ogc.v-sli.me)
  -d, --debug                Enable this flag causes logging in debug mode
  -h, --help                 help for this command
  -p, --page-domain string   Domain of the site used for the Post (Example: ogc.v-sli.me)
```

### âï¸ POST ãã¼ã¿

```json
{
  "text": "ãã¡ãã«45æå­ä»¥åã®æç« ãå¥å"
}
```

## âï¸ éçº

ãã®ãªãã¸ããªã®éçºãã©ã³ãã¯`develop`ãã©ã³ãã§ãã<br/>
PR ãéãå ´åã¯`develop`ãã©ã³ãã«éã£ã¦ããã ãã¨å©ããã¾ãã

```bash
git checkout develop
```

## ð ã©ã¤ã»ã³ã¹

MIT License
