[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=E3G6KRHXDUF98&lc=US&item_name=Help%20Developer%20Julio%20Lustosa&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

# Docker for Mailcatcher
```shell
docker pull juliolustosa/mailcatcher
```

### 1 - Example docker-compose.yaml
```yml
# docker-compose.yaml
version: '2'
services:
  mailcatcher:
    image: juliolustosa/mailcatcher
    ports:
      - "1025:1025"
      - "1080:1080"
```

Mailcatcher website https://mailcatcher.me/
