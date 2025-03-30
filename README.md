# 🎬 MovieVerse

A sleek movie browsing app built with **React**, **Appwrite**, and the **TMDB API**. Explore the latest movies, trending titles, and your favorites — all in one place.

## 🚀 Features

- 🔍 Browse and search for movies using TMDB's massive database  
- 📚 View detailed movie info including ratings, trailers, and overviews  
- ❤️ User authentication and personal movie lists powered by Appwrite  
- 🎨 Responsive and modern UI built with React

## 🛠 Tech Stack

- **React** – Frontend library  
- **Appwrite** – Backend-as-a-service for auth and database  
- **TMDB API** – Movie data source  
- **Tailwind CSS** – Utility-first CSS framework 


## 🧠 Inspiration & Credits

This project was built by following the [**MJ REACT Crash Course**](https://www.youtube.com/watch?v=dCLhUialKPQ&t=7387s&ab_channel=JavaScriptMastery) by **JavaScript Mastery** — a fantastic, beginner-friendly tutorial that walks through building a modern movie app using React, Appwrite, and TMDB.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- Git  
- Node.js  
- npm (Node Package Manager)

---

### Cloning the Repository

```bash 
git clone https://github.com/glebbogachev00/movie-app.git
cd movie-app
```

### Installation

```bash 
npm install
```

### Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content

```bash
VITE_TMDB_API_KEY=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
```
Replace the placeholder values with your actual TheMovieDatabase API and Appwrite credentials. You can obtain these credentials by signing up on the TheMovieDatabase and creating a new project on the Appwrite


### Running the Project

```bash
npm run dev
```
Open http://localhost:5173 in your browser to view the project.