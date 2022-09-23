Author: Ahnaf Azad

A news app that uses the RecyclerView in android studio to present users with breaking news within the past 24 hours, allowing the users to read the full article by opening a custom chrome tab in their phone screen without leaving the app
Created using: Kotlin, Android Studio, Volley, Glide 

The app uses a news API to get its data, presenting the users with a clickable thumbnail image on it's screen, along with the news title and its author. 
The Volley and Glide library is used to make the API calls and convert URLs to images. 
The RecyclerView model is used instead of a ListView to minimize the use of phone memory. 
The Chrome custom tab API is used to open the article URL without the user having to switch from the app to open chrome or any other internet browser, giving a seamless experience 
