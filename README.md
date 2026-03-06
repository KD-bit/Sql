# 🎬 Movie Streaming Platform – Mini Project

## 1. Project Proposal

### Project Title
Movie Streaming Platform

### Introduction
This project describes a web-based movie streaming platform where users can watch movies, TV series, cartoons, and anime online. The system allows users to search for movies, explore categories, and save their favorite content.

### Objectives
- Provide an easy way to watch movies online
- Allow users to search and filter movies
- Allow users to save movies to favorites
- Provide a simple and user-friendly interface

### Target Users
Students and general users who want to watch movies online.

### Main Features
- User registration and login
- Search movies
- Watch movies
- Add movies to favorites
- View watch history

---

# 2. Use Cases

## Use Case 1: User Registration

**Actor:** User  

**Description:**  
A user creates a new account to use the platform.

**Steps:**
1. User opens the registration page
2. User enters email and password
3. User clicks the register button
4. The system creates a new account

**Explanation:**  
This use case allows new users to register in the system.

---

## Use Case 2: Search Movie

**Actor:** User  

**Description:**  
User searches for a movie.

**Steps:**
1. User enters a movie name in the search bar
2. System processes the request
3. System shows a list of matching movies

**Explanation:**  
This feature helps users quickly find the movie they want.

---

## Use Case 3: Add Movie to Favorites

**Actor:** User  

**Description:**  
User saves a movie to their favorites list.

**Steps:**
1. User opens the movie page
2. User clicks "Add to Favorites"
3. The movie is saved to the favorites list

**Explanation:**  
Favorites allow users to save movies for later viewing.

---

# 3. Business Process Models (BPM)

## BPM 1: Watching a Movie

Start  
↓  
Open Website  
↓  
Login  
↓  
Search Movie  
↓  
Select Movie  
↓  
Click Play  
↓  
Watch Movie  
↓  
End  

**Explanation:**  
This process describes how a user watches a movie on the platform.

---

## BPM 2: User Registration

Start  
↓  
Open Registration Page  
↓  
Enter Email and Password  
↓  
Submit Form  
↓  
System Creates Account  
↓  
End  

**Explanation:**  
This process describes how a user creates an account.

---

## BPM 3: Searching for a Movie

Start  
↓  
Open Website  
↓  
Enter Movie Name  
↓  
System Searches Database  
↓  
Display Results  
↓  
End  

**Explanation:**  
This process shows how the system finds movies based on user input.

---

# 4. Screen Layouts

## Screen 1: Home Page

**Elements**
- Navigation bar
- Search bar
- Movie categories
- Movie cards

**Explanation:**  
The home page allows users to browse available movies and search for content.

---

## Screen 2: Movie Page

**Elements**
- Movie poster
- Movie title
- Movie description
- Watch button
- Add to favorites button

**Explanation:**  
This page shows detailed information about a selected movie.

---

## Screen 3: User Profile

**Elements**
- Username
- Watch history
- Favorites list

**Explanation:**  
The profile page allows users to manage their saved movies and viewing history.

---

# 5. ERD (Entity Relationship Diagram)

## Entities

### User
- user_id
- email
- password

### Movie
- movie_id
- title
- genre
- description

### Favorites
- id
- user_id
- movie_id

## Relationship

User  
↓  
Favorites  
↓  
Movie  

**Explanation:**  
The Favorites table connects users and movies. A user can save multiple movies to their favorites.

---

# 6. Database Tables

## Users Table

| Field | Type |
|------|------|
| id | Integer |
| email | Varchar |
| password | Varchar |

**Explanation:**  
Stores information about registered users.

---

## Movies Table

| Field | Type |
|------|------|
| id | Integer |
| title | Varchar |
| genre | Varchar |
| description | Text |

**Explanation:**  
Stores information about movies available on the platform.

---

## Favorites Table

| Field | Type |
|------|------|
| id | Integer |
| user_id | Integer |
| movie_id | Integer |

**Explanation:**  
This table stores which movies users added to their favorites.

---

# Conclusion

This mini project demonstrates the basic design of a movie streaming platform. The system includes user interaction scenarios, business processes, interface layouts, and database design. The goal is to create a simple and efficient platform for watching movies online.
