<p align="center">
  <img src="https://github.com/user-attachments/assets/4d8ca5fc-6030-4565-b56a-1551c815b930" alt="SOUNDTREK Logo" width="200" height="200">
</p>


# SoundTrek
Is a mobile application that transforms sightseeing into an immersive experience by providing **personalized audio explanations for landmarks** around you.  
The app combines **location-based recommendations, AI-powered route suggestions, and a clean, user-friendly design** to enhance every trip.

---

## Key Features

### 1. **Personalized Landmarks Discovery**
- View **nearby and recommended landmarks** based on your personal preferences.
- Explore detailed information for each landmark, including images and descriptions.

### 2. **Immersive Audio Guide**
- Select a **language** and a **storytelling genre** for each landmark.
- Listen to AI-generated audio explanations based on your selections.

### 3. **Search & Filters**
- Search for landmarks by name.
- Filter by categories such as Museums, Entertainment, Nature, etc.

### 4. **Smart Routes**
- **Custom Routes:** Manually select attractions and plan your own itinerary.
- **Recommended Routes:** Get AI-based suggestions (Gemini API) for an optimal route.
- Edit your route by reordering adding or removing landmarks.

### 5. **User Profile and Preferences**
- Update your **personal details**, **language**, **preferred search radius**, **liked landmarks**, and **interests**.

---

## Main Screens

- **Login / Sign Up**

  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 37 12" src="https://github.com/user-attachments/assets/a0a4daef-2227-40eb-86f7-ec49b2f53044" />
  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 37 24" src="https://github.com/user-attachments/assets/59db15be-5e85-4fc5-8d01-4846770699d3" />
  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 37 30" src="https://github.com/user-attachments/assets/69c31060-fc99-44fe-a54d-244c1be0392f" />
  
- **Home** – Grid of attractions (All / Recommended)
  
  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 39 46" src="https://github.com/user-attachments/assets/81d7bd31-62cd-4d16-a3ea-a56c262fd15e" />

  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 40 47" src="https://github.com/user-attachments/assets/f73096eb-3111-4831-af09-444bbafb1527" />

- **Search** – Search and filter attractions

  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 41 13" src="https://github.com/user-attachments/assets/2529cca2-cde9-4dc6-9313-90ff0f32d053" />

  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 41 41" src="https://github.com/user-attachments/assets/6ac6ca2b-d1f6-40d1-a636-2fe61a7fd8c3" />

- **Landmark Details** – Description, images, and Listen option

  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 42 21" src="https://github.com/user-attachments/assets/b157bb20-c97a-4bcc-ab35-aa2d34053334" />

  - **Language Selection**

    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 42 41" src="https://github.com/user-attachments/assets/7c6311a7-7ad7-4839-9032-85c296bdf8f3" />

  - **Genre Selection**
 
    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 42 58" src="https://github.com/user-attachments/assets/26103136-10bc-4407-a654-4380aa3585c5" />

    - **Audio Player**

      <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 43 45" src="https://github.com/user-attachments/assets/af58db13-d926-4d74-8dfa-0508ecb248b3" />

      <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 44 06" src="https://github.com/user-attachments/assets/cf21548e-d2c7-4b38-a11c-72e0f61087bb" />

- **Route Planning**

  <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 44 42" src="https://github.com/user-attachments/assets/a5f3127e-76e1-484b-b106-21d436b25ec1" />

  - Custom Route
    
    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 45 44" src="https://github.com/user-attachments/assets/04e1d5bc-a0df-4c55-b10b-28a432d75368" />

    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 45 28" src="https://github.com/user-attachments/assets/e0c81671-2a22-48e0-87cf-d70f344ca92c" />

  - Recommended Route

    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 50 06" src="https://github.com/user-attachments/assets/12932c56-7b6d-48b5-ae48-2e6a630a246c" />

  - Edit Route

    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 50 20" src="https://github.com/user-attachments/assets/b2948f81-5521-4a53-a684-1d53a81baa09" />

- **Profile**
  
    <img width="120" height="262" alt="Untitled" src="https://github.com/user-attachments/assets/593854ac-d9b8-4932-9ece-445a9bd14493" />
   
  - Edit selected parts of the profile
    
    <img width="120" height="262" alt="Simulator Screenshot - iPhone 16 Pro - 2025-07-31 at 15 57 07" src="https://github.com/user-attachments/assets/039a488f-37b8-419d-b27c-a913b4c4b7eb" />


---

## Technologies & Integrations

- **Frontend:** React Native + Expo App
- **Backend APIs:**
  - **Wikipedia API** – Landmark descriptions and details
  - **Gemini API** – Recommended routes and content personalization
  - **OpenRouteService API** – Route paths and navigation
- **Location Services:** Device GPS/Map

---

## Navigation Flow

```
Login / Sign Up
└── Home
    ├── Search
    │   ├── Search by Name
    │   └── Filter by Category
    ├── Landmark Details
    │   ├── Language Selection
    │   ├── Genre Selection
    │   └── Audio Player
    ├── Itinerary
    │   ├── Custom Route
    │   ├── Recommended Route
    │   └── Edit Route
    └── Profile
        └── Edit Profile sections
```

---

## How It Works

1. **Sign in or register** to start exploring.
2. **Discover landmarks** around you or based on tour prefernces.
3. Tap an attraction to view details, then if you want to listen to a customized audio explanation of the selected landmark:
   - Choose a **language** and **genre**.
   - **Listen**.
4. Plan routes:
   - Use **Custom Route** to manually choose attractions.
   - Use **Recommended Route** for AI-generated itineraries.
5. **Edit and plan routes**.
6. **update your preferences** in your profile.

---

## Status

SoundTrek was developed as part of our final project in our Computer Science degree.  
More changes might be made in the future.

---

## Authors

- **Or Dahan**  
- **Roni Ronen**  
- **Barak Doron**
