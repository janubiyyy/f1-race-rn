🏎️ F1 Race Simulation — Mobile & Web

Proyek ini merupakan implementasi simulasi balapan F1 menggunakan data nyata dari OpenF1 API serta drag & drop kontainer untuk pengaturan barang.

📂 Struktur Repository
.
├── f1-race-rn/     # Project Mobile (React Native + Expo)
├── f1-race-web/    # Project Web (Next.js + TypeScript)
└── README.md       # Dokumentasi ini

🚀 Cara Menjalankan
1️⃣ Clone Repository
git clone https://github.com/username/f1-race.git
cd f1-race

2️⃣ Menjalankan Project Web (Next.js)

Masuk ke folder:

cd f1-race-web


Instal dependency:

npm install
# atau
yarn install


Jalankan development server:

npm run dev
# atau
yarn dev


Buka di browser:
👉 http://localhost:3000

Fitur Web

📦 Drag & Drop barang ke dalam kontainer.

🎨 UI interaktif, responsif, dan menggunakan Tailwind CSS.

🖥 Bisa dijalankan di desktop & mobile browser.

3️⃣ Menjalankan Project Mobile (React Native + Expo)

Masuk ke folder:

cd ../f1-race-rn


Instal dependency:

npm install
# atau
yarn install


Jalankan Expo:

npm start
# atau
yarn start


📱 Scan QR code menggunakan aplikasi Expo Go di HP (Android/iOS).
Atau jalankan di emulator:

npm run android
# untuk Android emulator

npm run ios
# untuk iOS simulator (hanya macOS)

Fitur Mobile

🏎 Simulasi balapan F1 menggunakan data dari OpenF1 API.

📊 Visualisasi progres pembalap di lintasan.

🗂 Navigasi menggunakan Bottom Tabs.

⚙️ Prasyarat

Node.js minimal versi 18

npm atau yarn

Untuk mobile:

Install Expo CLI global:

npm install -g expo-cli


Jika pakai emulator:

Android: Android Studio + AVD

iOS: Xcode (khusus macOS)

📦 Script Penting
Web (Next.js)

npm run dev → Jalankan development server

npm run build → Build untuk production

npm run start → Jalankan hasil build

Mobile (React Native + Expo)

npm start → Jalankan dengan Expo Go

npm run android → Jalankan di emulator Android

npm run ios → Jalankan di simulator iOS

📝 Catatan

Pastikan internet tersedia karena mobile app mengambil data dari OpenF1 API.

Jika mengalami error di React Native:

Hapus cache:

npm start -- --reset-cache


Reinstall dependency:

rm -rf node_modules && npm install

👨‍💻 Author

Tasya Khaerani
