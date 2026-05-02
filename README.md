**WordSearch App (Single Page Dictionary Application**

WordSearch App is a Single Page Application that allows users to search for English words and view their definitions, pronunciation, and synonyms. It also allows users to save favorite words and listen to pronunciation audio when available.

## Features

- Search for word definitions using a Dictionary API
- Display meanings, pronunciation, and synonyms
- Play pronunciation audio (when available)
- Save and remove favorite words
- Store favorites using localStorage
- Clear search results without reloading the page
- Fully dynamic single page application (SPA)

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API
- Async / Await
- LocalStorage
- 
  ## API Used

This project uses the Free Dictionary API:

https://api.dictionaryapi.dev/

The API provides:
- Word definitions
- Pronunciation data
- Phonetics audio
- Synonyms

  ## How It Works

1. User enters a word into the search bar
2. The application sends a request to the Dictionary API
3. API returns word data (definition, pronunciation, etc.)
4. The page updates dynamically without reloading
5. Users can:
   - Save words to favorites
   - Play pronunciation audio
   - Clear search results
  
     ## Favorites Feature

- Users can save words as favorites
- Favorites are stored in localStorage
- Data remains saved even after page refresh
- Users can remove words from favorites

---

## Audio Feature

- Some words include pronunciation audio from the API
- Users can play audio directly in the app
- If audio is unavailable, the feature is disabled

---

## Future Improvements

- Display full favorites list on page load
- Add dark mode support
- Improve UI design with cards and layout improvements
- Add example sentences for words

  ## Author

I built this app to practice working with external APIs and async JavaScript

---

## License

This project is for educational purposes and is open for learning and modification.
