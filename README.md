## Intro
Imagine you are contributing to the development of a large-scale platform, which consists of various client websites, services (including a **blockchain** component), and a comprehensive database. Your current focus is on integrating the backend with the `market` front-end application.

Front-end application will consist of such pages:
- **Main page**
- **Page of all Art Assets** (_featuring pagination, sort, filters, etc_)
- **Page of single Art Asset**
- **Page of all Artists** (_featuring pagination, sort, filters, etc_)
- **Page of single Artist**
- **Page of search** (_for searching artists and art assets_)
- **Contacts page**

## Task
Your task is to develop functionality to retrieve data for the **Single Art Asset Page**. The relevant part of the database tables is stored in `db/db.sql`. The data required for the page must include:
1. Art Asset details:
    - original name
    - english name
    - description
    - price
    - filename of the files on the disk (`filename_disk`)
2. Information related to the Artists associated with the Art Asset:
    - name
    - filename of photo (`filename_disk`)
3. Details of 4 Art Assets from an Artist associated with the primary Art Asset (for block _'More from artist'_):
    - original name

## Requirements
1. TypeScript
2. Express.js
3. PostgreSQL

#### Considered a plus if you can:
Execute raw database queries or utilize [Knex.js](https://knexjs.org/)
