```bash
openssl s_client -showcerts -connect site.ru:443 </dev/null | openssl x509 -noout -dates
```

#useful