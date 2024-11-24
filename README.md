## Project Overview

This project is a Flutter application that includes a backend API and a prediction model. The directory structure is organized as follows:

Summatives/
├── Api/ # Contains the backend API
│ └── main.py # Main API file
├── Model/ # Contains the prediction model
│ └── model.py # Prediction model file
└── persona_r/ # Flutter mobile application
└── lib/ # Flutter app source code

## API Endpoint
API endpoint: https://my-fastapi-wxqz.onrender.com/predict
Use this swagger docs on how to use it: https://my-fastapi-wxqz.onrender.com/docs

# Demo Video
video link: https://youtu.be/VKxlmmV5FMI

## Mobile App
To run the Flutter mobile app, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the `persona_r` directory:
   ```bash
   cd persona_r
   ```
3. Install the necessary dependencies using:
   ```bash
   flutter pub get
   ```
4. Start the development server with:
   ```bash
   flutter run
   ```
5. Open your emulator or connect a physical device to view the app.

## Additional Notes
- Ensure you have Flutter installed on your machine. You can follow the installation guide [here](https://flutter.dev/docs/get-started/install).
- The API must be running for the app to function correctly. Make sure to start the API server before running the Flutter app.