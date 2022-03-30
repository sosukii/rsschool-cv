# Svetlana Trukhina

<img src="./myphoto.jpg" width="110" alt="my photo here">

## Contact me  

Telegram: @Tasvetla \
Email: sweta4ca@mail.ru \
Phone: +7 999 499 7861 \
RS school nickname (diskord): sosukii (@sosukii) sosukii#4767

---

## About myself

I want to doing my best for comfort life of my family, myself and my friends. \
My meaning - it is give you a free time: for generete a new buisness strategy, thinking about risk, loyality (to get royalty), and time to visit you're grandphather too. Work for result, but do not remember take a rest (if you don't wont to be a fire off and become dying dry flower)

---

### I want to help you, and how can i do this

- i will see which process you want to see in you're buisness;
- i am thinking about it and will offer you automatization solutions;
- we going to diskass it, choose most affordable/suitable solve.

And when all disputes moments has been solved, we can start to code it up.

## Skills

html, css, js, react, mongodb, mongoose, git/githab

---

### Code example

(one of parser function)

```javascript
async function getDataFromCards (cardsAtOnePage){
            for (let oneCard of cardsAtOnePage){
                let name = await oneCard.$eval('div.title-image > div.title-wrap > a', e => e.textContent)
                let textPrice = (await oneCard.$eval('div.catalog-item-price > ul ', e => e.textContent)).split('Розничная цена: ')[1]
                let price = (textPrice.split('.00 Р')[0]).replace(' ','')

                let amount = '1'
                let isNotAvailable = await oneCard.$eval('div.catalog-item-quantity-wrap.authorized > div.catalog-item-quantity > div.region-quantity', e=> e.textContent.includes('Нет'))

                if(isNotAvailable){
                    amount='0'
                }
                if(price.includes('запросу')){
                    price=''
                    amount='0'
                }

                let obj = {name,price,amount,enabled:'+',currency:'RUB'}
                arrayData.push(obj)
            }
        }
```

---

## Work expiriance

1. [Parsers](https://github.com/sosukii/3parsers_exe). Creating with puppeteer\cheerio, nodejs, fs;

    ![NodeJS](https://img.shields.io/badge/-NodeJS-9c5?style=flat&logo=node.js)
    ![JavaScript](https://img.shields.io/badge/-JavaScript-000?style=flat&logo=javascript)
    ![Puppeteer](https://img.shields.io/badge/-Puppeteer-fff?style=flat&logo=puppeteer)

2. [CRM](https://github.com/sosukii/crm). Creating with react, nodejs, express, mongoDB, mongoose;

    ![NodeJS](https://img.shields.io/badge/-NodeJS-9c5?style=flat&logo=node.js)
    ![JavaScript](https://img.shields.io/badge/-JavaScript-000?style=flat&logo=javascript)
    ![React](https://img.shields.io/badge/-React-000?style=flat&logo=react)
    ![MongoDB](https://img.shields.io/badge/-MongoDB-000?style=flat&logo=mongodb)

3. [Test projects](https://github.com/sosukii/booksAuthors). Creating with react, nodejs, express, couchDB, graphQL.

    ![NodeJS](https://img.shields.io/badge/-NodeJS-9c5?style=flat&logo=node.js)
    ![JavaScript](https://img.shields.io/badge/-JavaScript-000?style=flat&logo=JavaScript)
    ![React](https://img.shields.io/badge/-React-000?style=flat&logo=react)
    ![CouchDB](https://img.shields.io/badge/-CouchDB-dd2427)
    ![GraphQL](https://img.shields.io/badge/-Graphql-da0093?style=flat&logo=graphql)

---

## Education

2020 TSPU / FACULTY OF PSYCHOLOGY AND SPECIAL EDUCATION

---

## Languages

Russian: native \
English: A2
