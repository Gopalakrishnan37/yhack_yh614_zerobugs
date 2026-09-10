# Factory Guardian

Build a responsive factory noise monitoring dashboard with a dark industrial theme.
- Display data for 2 zones: Assembly Line and Compressor Room.
- Live noise level metric cards with status indicators (Green for Normal <= 85dB, Red for Alert/High noise > 85dB).
- Interactive charts showing noise trends over time.
- Mobile-friendly, responsive layout.
- Integrate Firebase Realtime Database using config:
const firebaseConfig = {
  apiKey: "@secret:GOOGLE_API_KEY",
  authDomain: "factory-noise-monitor.firebaseapp.com",
  databaseURL: "https://factory-noise-monitor-default-rtdb.firebaseio.com",
  projectId: "factory-noise-monitor",
  storageBucket: "factory-noise-monitor.firebasestorage.app",
  messagingSenderId: "262830353806",
  appId: "1:262830353806:web:847d2b2d8bb9b7d0b408df",
  measurementId: "G-CRRWF70JZ6"
};
- Read live data dynamically from the 'zones' path in Firebase Realtime Database, including fallback/demo states if the database is initially empty.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/86da9375-07d1-4329-9560-3d8dd9b949a0).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
