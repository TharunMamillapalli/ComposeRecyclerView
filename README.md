# Compose RecyclerView App

This project demonstrates how to build a movie/TV show browsing app using **Jetpack Compose**. 
It features a `LazyColumn` for displaying a list of TV shows and allows navigation to a detailed view when an item is clicked. The app is built entirely with **Kotlin** and adheres to modern Android development practices.

---

## **Features**

- **Jetpack Compose UI**: Declarative and reactive user interfaces built using Compose.  
- **LazyColumn for Lists**: Efficient list rendering and scrolling support.  
- **Composable Components**: Reusable UI components such as `TvShowListItem` and `TvShowImage`.  
- **Navigation**: Navigate to a detailed view of selected TV shows.  
- **Material 3 Design**: Styled with Material Design 3 principles.  
- **Dynamic Data**: Populates UI with a list of TV shows.

---

## **Code Overview**

### **Main Components**

1. **DisplayTvShows**  
   Displays a list of TV shows using `LazyColumn` and handles item selection through a callback.

2. **TvShowListItem**  
   Represents a single list item, displaying TV show details such as name, overview, year, and rating. Implements click functionality to navigate to detailed information.

3. **TvShowImage**  
   Displays the thumbnail image of the TV show with proper scaling and styling.

---

## **Technologies Used**

- **Kotlin**  
- **Jetpack Compose**  
- **Material Design 3**  
- **LazyColumn** for lists  
- **Composable functions** for UI modularization  

---



Feel free to use this project as a learning reference for **Jetpack Compose** and **Kotlin-based UI development**!
