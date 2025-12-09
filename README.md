# GoCart – Real-Time Nearby Vegetable Vendor Locator

## 🛒 Overview  
GoCart is a real time location based mobile application that helps users find nearby vegetable vendors who sell vegetables using carts or electric vehicles.  
The app shows **live vendor locations**, lets users **view vendor inventory**, **add items to cart**, and **place orders** directly from the vendor.

Built using **React Native (Expo)**, **Firebase**, and **Mapbox**, GoCart improves the experience of buying fresh vegetables locally.

---

## ✨ Key Features  

### 🔍 1. Find Nearby Vendors  
- Detects user location  
- Shows all vegetable vendors within **2 km radius**  
- Displays **live vendor movement** on Mapbox  
- Vendors update their location in real time from vendor-side app

### 🛒 2. Vendor Inventory & Cart  
- View vegetables with price & quantity  
- Add items to cart  
- Edit or remove items  
- Quantity validation based on vendor stock  
- Upload orders to Firebase with *pending / completed* status  

### 📍 3. Live Mapbox Integration  
- Smooth map rendering  
- Real-time vendor markers  
- Distance-based filtering  
- Vendor details on map tap

### 🧾 4. Vendor Management (Vendor App)  
- Vendors can add, update, and delete vegetables  
- Inventory syncs instantly with Firebase  
- Update price & quantity through a modal  
- Delete confirmation dialogs  
- Firestore-based CRUD operations

### ⭐ 5. Rating & Reviews  
- Users can rate vendors after order delivery  
- Ratings stored in Firebase  
- Vendor rating displayed on vendor profile

---

## 📁 Project Structure  
```
/app
/assets
/components
/context
/hooks
/screens
/services       # Firebase, Mapbox APIs
/utils
package.json
```

---

## 🚀 Getting Started

### Prerequisites  
- Node.js  
- Expo CLI  
- Firebase project  
- Mapbox access token  

### Installation  
```bash
git clone https://github.com/VinayakBadole/Go-Cart-App.git
cd Go-Cart-App
npm install
npm start
```

### Environment Variables  
Create a `.env` file (do NOT commit this):  
```
 
EXPO_PUBLIC_FIREBASE_API_KEY=
EXPO_PUBLIC_FIREBASE_AUTH_DOMAIN=
EXPO_PUBLIC_PROJECT_ID=
EXPO_PUBLIC_STORAGE_BUCKET=
EXPO_PUBLIC_MESSAGING_SENDER_ID=
EXPO_PUBLIC_APP_ID=
EXPO_PUBLIC_MEASUREMENT_ID=
EXPO_PUBLIC_MAPBOX_KEY=
EXPO_SECRET_MAPBOX_KEY=
MAPBOX_MAPS_DOWNLOAD_TOKEN=
EXPO_PUBLIC_SUPABASE_URL = 
EXPO_PUBLIC_SUPABASE_ANON_KEY =
```

---

## 🗂 Files to Exclude (Important)  
Your `.gitignore` must exclude:  
```
node_modules/
.expo/
.env
android/
ios/
.vscode/
build/
```

---

## 📦 Tech Stack  
- **React Native (Expo)**
- **Firebase Firestore**
- **Mapbox Maps SDK**
- **Context API** for cart & state management
- **JavaScript / TypeScript (optional)**

---

## 🧪 Future Improvements  
- Order tracking with Estimated Time  
- Payment gateway integration  
- Push notifications  
- AI-based vendor recommendations  

