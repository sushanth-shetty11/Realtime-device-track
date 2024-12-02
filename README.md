# Real-Time Device Tracking

A real-time device tracking system that uses geolocation to track the location of devices on a map. The application allows you to view the real-time location of multiple devices as they move, and it uses **Socket.IO** for real-time communication and **Leaflet** for map rendering.

## Features

- Real-time location tracking of devices using **Geolocation API**.
- Map rendering using **Leaflet** with OpenStreetMap tiles.
- Real-time updates using **Socket.IO** to broadcast location changes to all connected clients.
- Displays markers on the map for each tracked device and updates their positions dynamically.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for Node.js.
- **Socket.IO**: Real-time, bidirectional communication between the server and clients.
- **Leaflet**: JavaScript library for interactive maps.
- **EJS**: Embedded JavaScript templating engine for rendering dynamic HTML.
- **Nodemon**: Tool for automatically restarting the application during development.

## Installation

To get started with this project, follow these steps:

1. Clone the repository:

git clone https://github.com/sushanth-shetty11/Realtime-device-track.git

2. Install dependencies:
Navigate into the project directory and install the required dependencies:
cd Realtime-device-track
npm install

3. Run the application:
Start the application using nodemon:
nodemon app.js

The server will run on http://localhost:3000.

4. Open your browser:
Navigate to http://localhost:3000 to view the application.

How It Works
The app uses navigator.geolocation to get the real-time location of the device.
This location is sent to the server using Socket.IO.
The server broadcasts this location to all connected clients.
On the client side, Leaflet is used to show the devices on a map and update their positions in real-time.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -m 'Add feature-name').
Push to the branch (git push origin feature-name).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or suggestions, feel free to reach out!

Author: Ranjith Shetty
GitHub: https://github.com/sushanth-shetty11


### Key Sections in the `README.md`:

- **Project Description**: Summary of the project's purpose and features.
- **Technologies Used**: Technologies that power the project.
- **Installation Instructions**: How to set up the project on your local machine.
- **How It Works**: A brief explanation of how the application functions.
- **Contributing**: Instructions for contributing to the project.
- **License**: Specifies the open-source license.
- **Contact**: Provides a way to reach out to you.

This gives a clear, one-page overview of the project and can be shared with collaborators or users. Let me know if you need any modifications!
