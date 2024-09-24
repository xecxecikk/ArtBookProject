
# ArtBookProjects

This project is an iOS app that allows users to manage a collection of paintings. Users can add, view, and delete paintings from a list stored using Core Data.

# Features

View List of Paintings: Paintings are displayed in a UITableView.
Add New Paintings: Users can navigate to a details screen to add new paintings.
Delete Paintings: Swipe-to-delete functionality is available to remove paintings from the list and Core Data.
Persistent Storage: Paintings are stored using Core Data, ensuring data is saved between app launches.
Project Structure



ViewController.swift
Manages the main view with the list of paintings.
Implements UITableViewDelegate and UITableViewDataSource to handle table view logic.
Handles fetching and deleting paintings from Core Data.
Adds a button in the navigation bar for adding new paintings.
DetailsVC.swift
Manages the details view where users can add or view details of a painting.
This file is responsible for saving new entries to Core Data.
Core Data Integration

The app uses Core Data to persist paintings. It interacts with the Paintings entity, which includes the following attributes:

name: The name of the painting.
id: A unique identifier for each painting (UUID).
Installation

To run the project:

Clone the repository:
bash
Kodu kopyala
git clone https://github.com/your-username/paintings-app.git
Open the project in Xcode.
Run the app on a simulator or a connected device.
Usage

Viewing Paintings: The main screen displays a list of stored paintings.
Adding a Painting: Tap the + button in the navigation bar to add a new painting.
Deleting a Painting: Swipe left on a painting in the list to delete it.

















https://github.com/user-attachments/assets/0924076f-07ba-4ff9-a8ee-1d513d493d01











