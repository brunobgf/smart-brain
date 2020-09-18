<h2 align="center">
  Smart-Brain
</h2>

<p align="center">
  <a href="#rocket-technologies"> :rocket: Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">💻 Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-execute">🔖 How To Execute</a>&nbsp;&nbsp;&nbsp;
</p>

<br>

## :rocket: Technologies

This project uses the following technologies:

- [React](https://reactjs.org)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Tilt](https://www.npmjs.com/package/react-tilt)
- [Tachyons](https://www.npmjs.com/package/tachyons)
- [Knex](http://knexjs.org/)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [Clarifai](https://docs.clarifai.com/)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)

## 💻 Project

Smart-Brain is a project that uses a Face Recognition API (Clarifai) to identify human faces!
The objective of this project was to use everything what we learned about Front-End, Back-End and Databases in the Course Complete Web-Developer: Zero To Mastery made by Andrei Neagoie and disponible currently in Udemy.
In this application besides the part of the face-recognition we also have a login and register options and they're registered on the Database. In order to make the passwords more secure this project used bcrypt. 

## 🔖 How To Execute

#### Cloning the project
```sh

git https://github.com/brunobgf/smart-brain.git

```
#### Installation 
In your Terminal, follow the instructions bellow to install the project dependencies. 
```sh

npm install 

```

#### Initializing the application 
```sh

cd front-end
cd back-end
psql -U postgres
npm start

```
