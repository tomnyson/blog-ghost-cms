## run install app
### install docker-composer first
```
docker-composer up -d
```
### update env

---
**NOTE**

you can change config of ghost at 
**ghost/config.production.json**

---
### config smtp
link: setup smtp here(https://www.sendinblue.com/free-smtp-server/)
```js
 "mail": {
    "from": "#",
    "transport": "SMTP",
    "options": {
      "host": "smtp-relay.sendinblue.com",
      "port": 587,
      "auth": {
        "user": "#",
        "pass": "#"
      }
    }
  },
```