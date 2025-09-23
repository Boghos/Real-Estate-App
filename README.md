# Real Estate App (In Progress)

A full-stack mobile Real Estate application built with **React Native**, **Expo**, **Appwrite**, **TypeScript**, and **Tailwind CSS**, featuring Google authentication, dynamic property listings, and user profiles. This project is currently in development as part of a learning initiative.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)

## Features

- **Authentication**: Secure Google sign-in using Appwrite.
- **Home Page**: Browse latest and recommended properties.
- **Explore Page**: Filter and search all types of properties.
- **Property Details**: View images, descriptions, and key property details.
- **Profile Page**: Manage user settings and profile info.
- **Reusable Architecture**: Modular and scalable components for future expansion.

## Tech Stack

- **React Native** – Cross-platform mobile framework
- **Expo** – Development tools and universal build system
- **Appwrite** – Backend-as-a-Service for authentication, database, and storage
- **TypeScript** – Type-safe JavaScript for scalable code
- **Tailwind CSS / NativeWind** – Utility-first styling for React Native

## Getting Started

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Boghos/Real-Estate-App.git
cd react_native-restate
```

**Installation**

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
```

Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the [**Appwrite Dashboard**](https://jsm.dev/rn25-appwrite).

**Start the app**

```bash
 npx expo start
```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).
