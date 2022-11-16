# P7 Groupomania

> Le projet 7 "Créez un réseau social d'entreprise" de la formation Developpeur Web d'Openclassrooms 
> Groupomania Social Network for Project 7 of Web Developper training by OpenClassrooms 

Powered with : 
- VueJS + axios
- NodeJs + express + mongoose
- MongoDB Atlas

To run this project, you will need:
```
NodeJs
npm
MongoDB Atlas
```

### Clone and install

Clone the project.
Go to the project directory.
Install dependencies.

  > If you have any trouble, check and update every package with `npm install -g npm-check-updates`.

### Environment Variables

To run this project, you will need to create a `.env` file in `back` folder. The add the following environment variables to the .env file

DB_HOST=
DB_USER= 
DB_PASSWORD= 
DB_NAME= 
TOKEN = 

Check `app.js` if you need more informations.

### Start the back

```bash
  cd ./back
  nodemon server or node server
```

### Start the front

```bash
  cd ./front
  npm run dev
```
You can go to http://127.0.0.1:5173 and enjoy !
