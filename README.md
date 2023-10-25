# Jobs App
This app fetches jobs using the JSearch API and displays them in a user friendly UI.

# Set Up
- Clone the repo:
```
git clone https://github.com/EdoardoCocconi/Jobs_App.git
```
- Install dependencies:
```
npm install
```
- Obtain a JSearch API key by visiting [this page](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch) You will have to create a Rapid API account
- create a .env file in the top directory and paste `RAPID_API_KEY=<YOUR KEY>`
- Download Expo Go on your phone
- Start the Expo development server and establishes a secure tunnel between your local machine and the Expo servers:
```
npx expo start --tunnel
```
- Scan the QR code with your phone and **the app will show up in Expo Go**