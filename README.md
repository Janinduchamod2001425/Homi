# 🏡 Homi - Full-Stack Real Estate Application


```Homi``` is a modern full-stack real estate application built with React Native and powered by Expo SDK 52, designed to deliver a seamless property browsing experience. With features like Google Authentication, Dynamic Property Listings, and User Profile Management, Homi ensures an intuitive and user-friendly platform for both property seekers and agents.

<img src="https://go-skill-icons.vercel.app/api/icons?i=reactnative,expo,typescript,tailwind,appwrite" />

# 🚀 Tech Stack
- Expo SDK 52: Streamlined mobile app development.
- React Native: Cross-platform mobile app development framework.
- TypeScript: Ensures type safety and clean code practices.
- Nativewind: Tailwind CSS styling optimized for React Native.
- Appwrite: Backend-as-a-service for authentication, database, and storage.
- Tailwind CSS: Modern utility-first styling framework.

## 🌟 Key Features
🔖 Authentication with Google:
Secure and seamless user sign-ins using Google’s authentication service.

🔖 Home Page:
Displays the latest and recommended properties with powerful search and filter functionality.

🔖 Explore Page:
Allows users to browse all types of properties with a clean and intuitive interface.

🔖 Property Details Page:
Provides comprehensive information about individual properties, including images, descriptions, and key details.

🔖 Profile Page:
Customizable user settings and profile management for a personalized experience.

🔖 Centralized Data Fetching:
Custom-built solution inspired by TanStack’s useQuery for efficient API calls, ensuring data consistency and performance.

🔖 Code Architecture & Reusability:
Modular code structure enabling scalability and easy maintenance.

### Start the app

```
npx expo start
```

### 🛠️ Set Up Environment Variables  

Create a new file named `.env.local` in the root of your project and add the following content:  

```env  
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1  
EXPO_PUBLIC_APPWRITE_PROJECT_ID=  
EXPO_PUBLIC_APPWRITE_DATABASE_ID=  
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=  
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=  
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=  
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=  

