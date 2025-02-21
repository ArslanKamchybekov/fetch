## **Fetch Rewards Coding Exercise - Android App (Jetpack Compose)**  

### **📌 Overview**  
This is a **native Android app** built using **Kotlin and Jetpack Compose** that fetches and displays a list of items from [Fetch Rewards API](https://fetch-hiring.s3.amazonaws.com/hiring.json).  

The app processes the data based on the following requirements:  
✔️ Groups items by `listId`.  
✔️ Sorts items **first by `listId`**, then alphabetically by `name`.  
✔️ Filters out items where `name` is **blank or null**.  
✔️ Displays the results in a **clean and readable UI**.  

---

### **🛠️ Tech Stack**  
- **Kotlin**  
- **Jetpack Compose** (for UI)  
- **Retrofit** (for network requests)  
- **Coroutines & Flow** (for async data handling)  
- **ViewModel** (for state management)  
- **Material 3** (for modern UI components)  

---

### **📦 Setup & Installation**  

#### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/ArslanKamchybekov/fetch.git
cd fetch
```

#### **2️⃣ Open in Android Studio**  
- Open **Android Studio** (latest stable version).  
- Select **"Open an Existing Project"** and choose the cloned repo.  
- Make sure your **Gradle syncs** successfully.  

#### **3️⃣ Run the App**  
- Connect an **Android device** (or use an emulator).  
- Click **Run ▶️** in Android Studio.  
- The app will fetch data and display the sorted list.  

---

### **📝 Features & Functionality**  
✅ **Fetches real-time data** from the API using Retrofit.  
✅ **Filters** out invalid entries (blank/null names).  
✅ **Sorts & groups** items by `listId`.  
✅ **Displays** the results in a neat, scrollable list (LazyColumn).  
✅ **Uses Jetpack Compose** for a modern UI experience.  

---

### **📌 API Endpoint**  
- Base URL: `https://fetch-hiring.s3.amazonaws.com/`  
- Endpoint: `hiring.json`  
