# Setup
1. Git clone
2. Node Verion : v_14 `nvm use 14`
3. yarn
4. Setup Export & Import
```
yarn strapi export -f msfda
>> msfda.tar.gz.enc

yarn strapi import -f msfda.tar.gz.enc --key msfda
```




usr : microsoft98piyu@gmail.com
pasw : Piyush9898

.env
HOST=0.0.0.0
PORT=1337
APP_KEYS=aB9+iuHi0XHgC0320gU71A==,ZU196uBhRzsap5D34Ck7ow==,sZ4XZKFX0ALAyuU0ajao0w==,rwQySIAfrddYdlB/8Amm9w==
API_TOKEN_SALT=TCbKtPRnNzshO9N6TG5C+w==
ADMIN_JWT_SECRET=82FK545fGc51AtIF1ubeew==
JWT_SECRET=6of/n3Hh6oxT/fyD6JribA==

HOST=0.0.0.0
PORT=1337
APP_KEYS=aB9+iuHi0XHgC0320gU71A==,ZU196uBhRzsap5D34Ck7ow==,sZ4XZKFX0ALAyuU0ajao0w==,rwQySIAfrddYdlB/8Amm9w==
API_TOKEN_SALT=TCbKtPRnNzshO9N6TG5C+w==
ADMIN_JWT_SECRET=82FK545fGc51AtIF1ubeew==
# Database
# DATABASE_CLIENT=sqlite
# DATABASE_CLIENT=postgres
# DATABASE_URL=
# DATABASE_HOST=localhost
# DATABASE_PORT=5432
# DATABASE_NAME=postgres
# DATABASE_USERNAME=postgres
# DATABASE_PASSWORD=postgres


# DATABASE_FILENAME=.tmp/data.db
# JWT_SECRET=sQtXBtSKdwmaoOs1NVtlzg==
JWT_SECRET=6of/n3Hh6oxT/fyD6JribA==
