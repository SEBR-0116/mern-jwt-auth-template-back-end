# Decoupled MERN Stack with JWT Auth Template - Back End

This is the back end of a decoupled MERN Stack app that includes JWT Authentication.


This project uses ES Syntax for the back end (Import instead of Require). You can re-configure these to match whichever syntax your app uses. If you want to use ES Syntax for yours, check the package.json file in this, note and copy the "type": "module", value found in it

## To Use This Template

- Attach your db or Atlas to your db/index.js file

- Run `npm i` to fetch the template's dependencies, and then install nodemon to your dev route:

```bash
npm i
```

```bash

npm i nodemon --save-dev
```

- touch a `.env` file:

```bash
touch .env
```

Fill it with the following:

```
DATABASE_URL=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

Replace the `DATABASE_URL`, `SECRET`, and `CLOUDINARY_URL` with values that you provide.

> 🚨 Place secrets in this `.env` file. The contents of this file WILL NOT be exposed to site visitors.

- Launch the app with nodemon


- Check the user's models to see what types of data you will need, then create a new user using Thunderclient to create your user and Token!
