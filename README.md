# Will It Rain On My Parade?
## **📖 Introduction**
Will It Rain On My Parade? is a visually immersive and highly dynamic weather forecast application designed to provide a beautiful and intuitive user experience. It goes beyond simple data display by creating a responsive atmospheric background that reflects the real-time weather conditions of the selected location. With a sleek, "liquid glass" interface and fluid animations, it makes checking the weather an engaging experience.

<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/f0f3138f-f026-46d0-bb9b-01b72db3b291" />


## ❗️ Important Note on API Keys
Please be aware that the "✨ Ask Gemini" feature requires a personal Google Gemini API key to function. This key is not provided with the project. You will need to obtain your own free key and insert it into the apiKey variable in the callGeminiApi function within the JavaScript code to enable the suggestion feature.

## 🚀 NASA Space Apps Challenge 2025
This project is a submission for the NASA Space Apps Challenge 2025 under the challenge category "Will It Rain On My Parade?". Our goal was to leverage weather data to create an application that is not only functional but also artistic and engaging, turning a simple weather check into a captivating visual experience.
 
## ✨ Features
- Live Weather Data: Fetches up-to-date, 7-day forecasts including daily and hourly breakdowns from the Open-Meteo API.

- Dynamic Animated Background: The entire background of the app is a live canvas that animates to match the current weather. This includes:

- Procedurally generated 3D clouds with realistic puffiness, texture, and shadows.

- Animated rain, complete with splashes.

- Intense thunderstorms with full-screen lightning bolts and internal cloud flashes.

- Comprehensive Search:

- Automatically get the weather for your current location using the browser's geolocation services.

- Search for any city or location worldwide.

- Directly input latitude and longitude coordinates for precise lookups.

- Detailed Forecasts:

- Switch between a 7-day daily forecast and an hourly forecast for the selected day.

- View detailed metrics like "feels like" temperature, humidity, wind speed, precipitation probability, and more.

- AI-Powered Suggestions: An integrated "Ask Gemini" feature provides creative and context-aware activity suggestions based on the current weather conditions.

- Fully Responsive UI: The interface is built to be adaptive, scaling elegantly to provide an optimal experience on any device, from mobile phones to widescreen desktops.

- Modern Glassmorphism Design: The UI elements feature a translucent, "liquid glass" effect that blends beautifully with the animated background.

## 🏆 Project Milestones
- Phase 1: Core Functionality & UI/UX (Completed)
   - Foundation: Initial project setup and integration with Open-Meteo and Nominatim APIs.

   - UI Development: Created core components like search, daily/hourly forecasts, and the details panel.

   - Design: Implemented the initial glassmorphism design language.

- Phase 2: Dynamic Visuals & Animation (Completed)
   - Canvas Integration: Developed the HTML5 Canvas background for dynamic weather effects.

   - Atmospherics: Implemented procedural rain, splashes, and the initial 2D cloud system.

   - Storm Effects: Added thunderstorm and lightning animations.

- Phase 3: Realism & Immersion (Completed)
   - Cloud Overhaul: Re-engineered the cloud rendering system to create textured, puffy, and volumetric 3D clouds.

   - Advanced Effects: Implemented internal cloud lightning flashes for more realistic storms.

   - Fine-Tuning: Refined all weather animations for a more natural and fluid look.

- Phase 4: AI Integration & UI Polish (Completed)
   - Smart Features: Integrated the Google Gemini API for intelligent activity suggestions.

   - Responsiveness: Engineered a fully responsive UI that adapts fluidly to all screen sizes.

   - Final Polish: Enhanced UI/UX with readability improvements and refined animations.

- Phase 5: Future Goals
   - Historical Data: Plan to allow users to look up weather conditions for past dates.

   - Custom Alerts: Intend to let users set up notifications for specific weather conditions.

   - Sound Scapes: Add optional, subtle sound effects for rain and thunderstorms to enhance immersion.

## 🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS for a utility-first CSS framework.

APIs:

Open-Meteo API: For detailed and accurate global weather forecast data.

Nominatim API: For geocoding search queries to find latitude and longitude.

Google Gemini API: For generating intelligent, context-aware suggestions.

Graphics: HTML5 Canvas API for all real-time weather animations and effects.

## 🚀 How to Use
Initial Load: Upon opening the application, it will request permission to access your location to provide an immediate forecast for where you are.

Search for a Location: Type a city name, region, or coordinates (e.g., 40.71, -74.00) into the search bar at the top. A list of matching results will appear below.

Select a Forecast:

Click on any day in the daily forecast strip to view the weather summary for that day.

The hourly forecast will automatically update to show the conditions for the selected day.

Click on a specific hour to see the main display update with that hour's prediction and visual effects.

View Details: Click the "Show Details" button to slide up a panel containing more in-depth information like humidity, wind speed, and precipitation.

Get a Suggestion: Click the "✨ Ask Gemini" button to get a personalized activity suggestion based on the currently displayed weather.

## 🧑‍💻 Credits & Developers
This project was brought to life by a talented team of developers. Connect with them on LinkedIn:

Thomas Paul CJ: [LinkedIn](https://www.linkedin.com/in/thomaspaulcj/)

Adith Abhilash: [LinkedIn](https://www.linkedin.com/in/adithabhilash/)

Vidhusankar CH: [LinkedIn](https://www.linkedin.com/in/vidhusankar-c-h-a68716248/)

Tessa Johnson: [LinkedIn](https://www.linkedin.com/in/tessajohnson01/)

Priya Shaji: [LinkedIn](https://www.linkedin.com/in/priyashaji/)

Keerthana P: [LinkedIn](https://www.linkedin.com/in/keerthanapadmakumar/)
