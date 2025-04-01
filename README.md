# Bottle Collection API

Welcome to the **Bottle Collection API**! This project contains a collection of bottle data, including details such as capacity, material, year of production, lifespan, and supported temperature types.

## 📦 Features
- JSON-based data structure for easy integration
- Information about different types of bottles
- Lifespan and temperature compatibility included
- Image URLs for visualization

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/bottle-collection.git
cd bottle-collection
```

### 2️⃣ Install Dependencies (if needed)
This project currently uses a simple JSON file. However, if you plan to create an API for it, you may use Node.js:
```bash
npm install
```

### 3️⃣ Run the Project
You can serve the JSON data using a local server like `json-server`:
```bash
npx json-server --watch data.json --port 5000
```
Now, visit: `http://localhost:5000` to see the data.

## 📂 JSON Data Structure
```json
[
  {
    "id": 1,
    "name": "Coca-Cola Glass Bottle",
    "capacity": "250ml",
    "material": "Glass",
    "year": 1995,
    "lifespan": "Indefinite",
    "holds": "Cold only",
    "image": "https://example.com/coca-cola-glass-bottle.jpg"
  }
]
```

## 🌍 API Usage
If you're using `json-server`, you can fetch the data via:
```bash
GET http://localhost:5000/bottles
```

## 📜 License
This project is **open-source** and available under the **MIT License**.

---

Enjoy collecting bottles! 🍼🥤🔥

