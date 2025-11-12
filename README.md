# Memory Game (SwiftUI + MVVM)

A visually engaging Memory Matching Game built with SwiftUI using the Model-View-ViewModel (MVVM) architecture.
Players flip over cards to find matching pairs, with smooth animations, progress tracking, and a clean modular structure designed for scalability and learning.

## Features
* Flip animation using withAnimation and 3D card rotation
* MVVM architecture for clean separation of logic and UI
* "New Game" button to reset and reshuffle cards
* ProgressView bar that updates in real-time as players make matches
* Dynamic grid layout using LazyVGrid
* Smooth transitions and SwiftUI-based animations

## Project Structure
* Card.swift: Defines the Card model, including properties like isFaceUp, isMatched, and imageName.
* MemoryGameViewModel.swift: Contains all business logic - creating cards, handling taps, checking for matches, updating progress, and resetting the game.
* ContentView.swift: The main SwiftUI view that displays the grid, progress bar, and controls.
