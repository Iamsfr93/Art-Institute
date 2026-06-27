🎨 Art Institute

A modern iOS application built with SwiftUI that allows users to browse artwork from the Art Institute of Chicago API. This project demonstrates API integration, MVVM architecture, asynchronous networking, JSON decoding, and modern SwiftUI navigation.

⸻

📖 Overview

The Art Institute app retrieves artwork information from the Art Institute of Chicago’s public API and presents it in a clean, searchable interface. Users can browse artworks, search by title or artist, and view detailed information for each artwork.

This project was developed as part of the MWD3A – iOS Development course using SwiftUI and follows the MVVM (Model-View-ViewModel) architecture.

⸻

✨ Features

* Browse artwork from the Art Institute of Chicago
* Search artworks by title or artist
* View detailed artwork information
* Asynchronous image loading with AsyncImage
* Pull-to-refresh support
* Loading indicator during network requests
* Error handling with alerts
* About screen
* Clean MVVM architecture

⸻

🛠 Technologies Used

* Swift 5
* SwiftUI
* Combine
* URLSession
* JSONDecoder
* Codable
* AsyncImage
* MVVM Architecture
* Xcode

⸻

📂 Project Structure

ArtInstitute
│
├── Model
│   ├── Artwork.swift
│   ├── ArtworkResponse.swift
│   └── Thumbnail.swift
│
├── ModelView
│   └── ArtworkStore.swift
│
├── Services
│   └── ArtAPIService.swift
│
├── View
│   ├── ArtworkListView.swift
│   ├── ArtworkDetailView.swift
│   └── AboutView.swift
│
├── ContentView.swift
└── ArtInstituteApp.swift

⸻

🧠 SwiftUI Concepts Demonstrated

* MVVM Architecture
* REST API Integration
* URLSession Networking
* JSON Decoding
* Codable Models
* ObservableObject
* @Published Properties
* NavigationStack
* NavigationLink
* State Management
* Search Functionality
* AsyncImage
* Pull to Refresh
* Error Handling

⸻

📸 Screenshots

Artwork List

Add screenshot here

Search

Add screenshot here

Artwork Details

Add screenshot here

About Screen

Add screenshot here

⸻

🚀 Future Improvements

* Display additional artwork metadata
* Add favorites functionality
* Offline caching
* Category filtering
* Sorting options
* Improved UI animations
* Dark mode enhancements

⸻

👨‍💻 Author

Syed Fahad Rasheed

* Aspiring iOS Developer
* Swift • SwiftUI • Java • Git • GitHub

⸻

📚 Course Information

Course: MWD3A – iOS Development

Assignment: Assignment 6 – Art Institute App

Institution: triOS College
