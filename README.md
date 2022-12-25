Docker compose to use trafik as a reverse proxy for [nostr-rs-relay](https://sr.ht/~gheartsfield/nostr-rs-relay/) with tls

Create letsencrypt folder 
```
mkdir letsencrypt
touch letsencrypt/acme.json # create the file
echo "{}" > letsencrypt/acme.json # fill the file with an empty json object
chmod 600 letsencrypt/acme.json # set the permissions
```

Change Email and domain in docker compose file 

Change relay url in config

Credits:
https://thomasventurini.com/articles/setup-ssl-with-traefik-and-lets-encrypt/


