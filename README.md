# Decoupled MERN Stack with JWT Auth Template - Back End

This is the back end of a decoupled MERN Stack app that includes JWT Authentication.


This project uses ES Syntax for the back end (Import instead of Require). You can re-configure these to match whichever syntax your app uses. If you want to use ES Syntax for yours, check the package.json file in this, note and copy the "Module:true" value found in it

## To Use This Template

- Attach your db or Atlas to your db/index.js file

- Run `npm i` to fetch the template's dependencies:

```bash
npm i
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

Launch the app with:

```bash
nodemon
```

You're done!
