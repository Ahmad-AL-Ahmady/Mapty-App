# Mapty - Map Your Workouts
![image](https://github.com/user-attachments/assets/19b82d9e-5327-4b83-9880-32041f042859)

Mapty is an interactive web application that allows users to log their workouts on a map. Users can input details about their running or cycling activities and view them visually on a map. The app stores workouts locally, allowing users to delete individual workouts or clear all workouts.

## Table of Contents

- [Description](#description)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Acknowledgments](#acknowledgments)

## Description

Mapty is designed to provide a simple and user-friendly interface for fitness enthusiasts to keep track of their workouts. The app uses geolocation to display a map centered on the user's current location, and users can add running or cycling workouts by clicking on the map. Each workout entry is saved with details like distance, duration, pace/speed, and cadence/elevation gain. The app offers the functionality to view all saved workouts, and delete them if needed.

## Demo

Check out the live demo of the App [Mapty App](https://mapty-alahmady.netlify.app/)

## Features

- **Geolocation**: Automatically detects user's location to initialize the map.
- **Workout Logging**: Users can add new running or cycling workouts with various details.
- **Map Integration**: Displays workouts on a map using Leaflet.js.
- **Persistent Storage**: Stores workouts in the browser's local storage for persistence across sessions.
- **Delete All Workouts**: Option to delete all workouts from the app.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/mapty.git
   cd mapty
   ```
2. **Open the App**: Open the `index.html` file in any web browser.

## Usage

- **Log a Workout**: Click anywhere on the map to add a workout, fill in the required details in the form, and submit.
- **Delete Workouts**: Click the "Delete all workouts" button to clear all stored workouts.
- **View Workouts**: View the logged workouts listed on the sidebar or click on the map markers.

## Technologies

- **HTML5** and **CSS3** for structure and styling.
- **JavaScript** for functionality.
- **Leaflet.js** for interactive maps.
- **Google Fonts** for typography.

## Acknowledgments

- The initial HTML and CSS were developed by [Jonas Schmedtmann](https://twitter.com/jonasschmedtman) for educational purposes. Additional modifications and functionality were added by me to enhance the application.
