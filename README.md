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

### Prerequisites

- Node.js
- npm or yarn
- Git
- Expo CLI (npm install -g expo-cli)

### Installation

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   git clone https://github.com/adrianhajdin/react_native-restate.git  cd React_Native_RealEstate  npm install   `

### Environment Setup

Create a .env.local file in the root directory and add your Appwrite credentials:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   EXPO_PUBLIC_APPWRITE_ENDPOINT=YOUR_APPWRITE_ENDPOINT  EXPO_PUBLIC_APPWRITE_PROJECT_ID=YOUR_PROJECT_ID  EXPO_PUBLIC_APPWRITE_DATABASE_ID=YOUR_DATABASE_ID  EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=YOUR_GALLERIES_ID  EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=YOUR_REVIEWS_ID  EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=YOUR_AGENTS_ID  EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=YOUR_PROPERTIES_ID   `

### Running the App

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   npx expo start   `

Then open in:

- **Development Build**
- **Android Emulator**
- **iOS Simulator**
- **Expo Go**
