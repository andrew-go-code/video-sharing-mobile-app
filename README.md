# Video sharing mobile application

## Description
This is a mobile application that allows users to share videos with other users.
The application is built using React Native, Expo, and Appwrite.

## Features
- User authentication
- Video upload
- Video playback
- Video search

## Launch
lib/appwriteConfig.js file should be created 
```javascript
export const appwriteConfig = {
	endpoint: "https://cloud.appwrite.io/v1",
	platform: "com.jsm.aora",
	projectId: "...",
	databaseId: "...",
	userCollectionId: "...",
	videoCollectionId: "...",
	storageId: "..."
};
```