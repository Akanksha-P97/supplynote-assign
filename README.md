URL shortener API built with NestJS and PostgreSql as Database

## Technologies


- [NestJS](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [TypeORM](https://typeorm.io/)
- [Nano-ID](https://www.npmjs.com/package/nanoid)
- [Class-validator](https://www.npmjs.com/package/class-validator)
- [Class-transformer](https://www.npmjs.com/package/class-transformer)

## Features 

- [x]  Shorten a URL
- [x]  Return shortened URL

## Testing the API
Run this command to make a sample POST request:
curl -d "{\"longUrl\":\"http://llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch.co.uk\"}" -H "Content-Type: application/json" http://localhost:3000/shorten


You will receive a short URL as a response, such as the following example:

http://localhost:3000/MWBNHDiloW


