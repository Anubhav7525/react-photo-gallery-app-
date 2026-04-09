
# 📸 React Photo Gallery App

A modern and responsive Photo Gallery application built using React.js. This app allows users to search and explore images with a clean UI and smooth user experience.

---

## 🚀 Features

* 🔍 Search images using keyword
* 🖼️ Responsive image gallery (grid layout)
* ⬇️ Load More functionality (pagination)
* 🎯 Hover effects and smooth UI
* ❌ Clear search option
* ⚡ Fast and optimized performance

---

## 🛠️ Tech Stack

* React.js
* JavaScript (ES6+)
* HTML5 & CSS3
* API Integration (for fetching images)

---

## 📂 Project Structure

src/
│── components/
│── App.js
│── index.js
│── styles.css

---

## ▶️ How to Run Locally


## Setup a cloundinary account

You'll need to create a cloudinary account [https://cloudinary.com/users/register/free](here) - there is a free tier.

## Start the server

- Clone the repo
- In the `api` folder, create a new file called `.env`. In here, add your cloudinary connection details e.g:

```

API_KEY={YOUR_API_KEY}
CLOUD_NAME={YOUR_CLOUD_NAME}
API_SECRET={YOUR_API_SECRET}

```

- You can get this from your cloudinary dashboard after signing up. **Avoid checking these details in to a public repo - this is effectively your username and password so keep em safe! :) **

- Open a terminal and run the following from the **API** folder:

```

npm install
npm run server

```

- You can check its working by going to `localhost:7000/photos` in Postman or Chrome

## Run the Frontend

**NOTE:** Make sure the Node server (in the API folder) is started otherwise the frontend won't work.

- Clone the repo
- In the `client` folder, create a new file called `.env`. In here, add an environment variable to point to the local node.js server e.g:

```

REACT_APP_API_URL=http://localhost:7000

```

- If you change the port the node server runs on for whatever reason make sure to change it here too

- Open a terminal and run the following from the **CLIENT** folder:

```

npm install
npm start

```

- The app should be running on `localhost:3000`
   

## 📌 Future Improvements

* 🔎 Image zoom (modal view)
* ❤️ Like/Favorite feature
* 🌙 Dark mode
* 📱 Better mobile responsiveness

---

## 🙌 Author

* Anubhav Dixit

---

⭐ If you like this project, give it a star on GitHub!

