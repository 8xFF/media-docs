---
title: Access Token
---

# Access Token

- Pregenerated token for default config:

WHIP: `eyJhbGciOiJIUzI1NiJ9.eyJyb29tIjoiZGVtbyIsInBlZXIiOiJwdWJsaXNoZXIiLCJwcm90b2NvbCI6IldoaXAiLCJwdWJsaXNoIjp0cnVlLCJzdWJzY3JpYmUiOmZhbHNlLCJ0cyI6MTcwMzc1MjI5NDEyMn0.EfRZK7eHMZ-TCG23-jst8TAKVfbiQhX21cxB2mSznAM`

WHEP: `eyJhbGciOiJIUzI1NiJ9.eyJyb29tIjoiZGVtbyIsInBlZXIiOm51bGwsInByb3RvY29sIjoiV2hlcCIsInB1Ymxpc2giOmZhbHNlLCJzdWJzY3JpYmUiOnRydWUsInRzIjoxNzAzNzUyMzE1NTgyfQ.6XS0gyZWJ699BUN0rXtlLH-0SvgtMXJeXIDtJomxnig`

RTMP: `eyJhbGciOiJIUzI1NiJ9.eyJyb29tIjoiZGVtbyIsInBlZXIiOiJydG1wIiwicHJvdG9jb2wiOiJSdG1wIiwicHVibGlzaCI6dHJ1ZSwic3Vic2NyaWJlIjpmYWxzZSwidHMiOjE3MDM3NTIzMzU2OTV9.Gj0uCxPwqsFfMFLX8Cufrsyhtb7vedNp3GeUtKQCk3s`

SDK: `eyJhbGciOiJIUzI1NiJ9.eyJyb29tIjoiZGVtbyIsInBlZXIiOm51bGwsInByb3RvY29sIjoiV2VicnRjIiwicHVibGlzaCI6dHJ1ZSwic3Vic2NyaWJlIjp0cnVlLCJ0cyI6MTcwMzc1MjM1NTI2NH0.llwwbSwVTsyFgL_jYCdoPNVdOiC2jbtNb4uxxE-PU7A`

Or create with token-generate api

```
atm0s-media-server --http-port 3100 token-generate
```

After that access http://localhost:3100/ui/ to create token by yourself, default cluster token is `insecure`
