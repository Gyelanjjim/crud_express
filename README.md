# crud_express.js

## ์ฃผ์ ๐
express.js ํ๋ ์์ํฌ์ TypeORM(pooling๊ธฐ๋ฅ)์ ์ฌ์ฉํ์ฌ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ Create, Read, Update, Delete API ์๋ฒ ๊ตฌ์ถํ๊ธฐ

## ๊ธฐ๊ฐ๐
2022.11.02 ~ 2022.11.02 (CommonJS๋ก ๊ตฌํ)<br />
2023.01.16 ~ 2023.01.17 (์ถ๊ฐ: ES๋ชจ๋๋ก ๊ตฌํ)

## ๋งํฌ๐
- [๊ธฐ์ ๋ธ๋ก๊ทธ](https://velog.io/@scroll0908/BENode-4.-Express์-TypeORM์-ํ์ฉํ-CRUD-API-๋ง๋ค๊ธฐ211.2)

## ๊ธฐ์ ์คํ
- JavaScript
- NodeJS
- ExpressJS
- MySQL
- TypeORM(Pooling ๊ธฐ๋ฅ๋ง ์ฌ์ฉ)

## ์ค๋ช
- ES๋ชจ๋๋ก ์๋ฒ ๊ตฌ๋ ์ package.js์์ "main"ํญ๋ชฉ ๋ค์์ `"type" : "module"` ์ถ๊ฐํด์ผ ํจ
- ES๋ชจ๋๋ก ์๋ฒ ๊ตฌ๋ ์ ๋ค์์ ์๋ฌ๊ฐ ์์ผ๋ฉฐ ์์ง ํด๊ฒฐํ์ง ๋ชปํจ
  > throw new MissingDriverError_1.MissingDriverError(type, [ 
MissingDriverError: Wrong driver: "undefined" given. ~
