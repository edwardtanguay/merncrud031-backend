# merncrud031-backend

this is an external fork of [Starter: Fullstack MERN site which allows user to add/edit/delete items via CRUD API using MongoDB and TypeScript/ES6-Modules on frontend/backend](https://starters.tanguay.eu/list/mernMongooseBookCrudFullstack)

## it adds the following feature

- **admin login** has been replaced by **multiuser login**

## changes

- [users.json](https://github.com/edwardtanguay/merncrud031-backend/blob/main/dev/users.json) file was added which should be imported into a collection in MongoDB called **users**
- [User model](https://github.com/edwardtanguay/merncrud031-backend/blob/main/src/models/User.ts) was added
- CLI command [npm run bcrypt](https://github.com/edwardtanguay/merncrud031-backend/blob/main/cli/bcrypt.mjs) was added to create password-hashes
