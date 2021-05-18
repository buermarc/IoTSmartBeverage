# Beverage Monitoring

## Current Structure

```
 .
├──  esp
│  ├──  data
│  ├──  esp.ino
│  ├──  keys
│  ├──  Makefile
│  ├──  private.key -> keys/private.key // MISSING
│  ├──  public.key -> keys/public.key
│  ├──  readme.txt 
│  ├──  secret.h // MISSING
│  ├──  self-signed-cert
│  └──  tools
├──  README.md
└──  update_server
   ├──  Cargo.lock
   ├──  Cargo.toml
   ├──  readme.txt
   ├──  self-signed-cert -> ../esp/self-signed-cert // MISSES PRIVATE KEY
   ├──  src
   └──  test-request.sh
```

## TODO: 
- Write the README
