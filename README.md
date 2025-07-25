<H1 align="center"> BertFlix (MERN MOVIE) </H1>
<h5 align="center">
Fullstack open-source movie application built with MongoDB, Express, React & Node.js (MERN)
</h5>
<br/>

  * [Configuration and Setup](#configuration-and-setup)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Frontend](#frontend)
      - [Backend](#backend)
      - [Database](#database)
      - [API](#api)
  * [Author](#author)
  

## Configuration and Setup

To run this project locally:

- Fork and clone the repository or download it as a ZIP file and extract it.
- Open the project in your preferred code editor.
- Open a terminal (VS Code: **Terminal > New Terminal**).
- Split your terminal into two (one for the client, one for the server).

### In the first terminal:

```
$ cd client
$ npm install (to install client-side dependencies)
$ npm run  start (to start the client)
```

In the second terminal

- Navigate to the server folder:

- Create a `.env` file and configure your environment variables:


#  --- .env  ---

MONGODB_URL
PORT =5000
TOKEN_SECRET=
TMDB_BASE_URL=
TMDB_KEY=
```

```
# --- Terminal ---

- Install dependencies and start the server:


$ npm install (to install server-side dependencies)
$ npm start (to start the server)
```


---

## Key Features

- User registration and login
- Authentication using JWT tokens
- Add/Delete Favorites
- Leave/Delete Reviews
- Password Update
- Real-time search
- Watch movie trailers on YouTube
- 404 Error Page
- Skeleton loading effects
- Dark Mode support
- Fully responsive design

<br/>

---

## Technologies Used

This project is powered by the following technologies:

### Frontend
- [React.js](https://www.npmjs.com/package/react) – Build user interfaces for single-page apps
- [React Hooks](https://reactjs.org/docs/hooks-intro.html) – State management
- [React Router DOM](https://www.npmjs.com/package/react-router-dom) – Routing
- [Axios](https://www.npmjs.com/package/axios) – API calls
- [Material UI](https://mui.com/) – UI components
- [React Redux](https://react-redux.js.org/) – State management
- [React Toastify](https://www.npmjs.com/package/react-toastify) – Toast notifications
- [Swiper](https://swiperjs.com/) – Sliders and carousels
- *(Optional)* [CK-Editor](https://ckeditor.com/) – Rich Text Editor
- *(Optional)* [Formik](https://formik.org/) – Form validation & handling

### Backend
- [Node.js](https://nodejs.org/en/) – JavaScript runtime
- [Express.js](https://www.npmjs.com/package/express) – Server and routing
- [Mongoose](https://mongoosejs.com/) – MongoDB modeling
- [Axios](https://www.npmjs.com/package/axios) – Server API calls
- [JSON Web Token](https://www.npmjs.com/package/jsonwebtoken) – Authentication
- [Cookie Parser](https://www.npmjs.com/package/cookie-parser) – Cookie handling
- [CORS](https://www.npmjs.com/package/cors) – Cross-origin requests
- [Dotenv](https://www.npmjs.com/package/dotenv) – Environment variable loader
- [Express Validator](https://www.npmjs.com/package/express-validator) – Input validation
- [Nodemon](https://nodemon.io/) – Development auto-reload

### Database
- [MongoDB](https://www.mongodb.com/) – NoSQL database

### API
- [TMDB API](https://developer.themoviedb.org/docs) – Movie and TV database API

---

## Author
- **GitHub:** [https://github.com/sahilkhan75](https://github.com/sahilkhan75)
- **LinkedIn:** [https://www.linkedin.com/in/sahil-khan-74a08635b/](https://www.linkedin.com/in/sahil-khan-74a08635b/)
- **Email:** sahilkhangoryan@gmail.com

#
