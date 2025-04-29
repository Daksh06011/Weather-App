# 🌦️ Weather App — Real-Time Weather with Node.js & Express

This is a simple and lightweight Node.js weather application that uses the OpenWeatherMap API to fetch real-time weather data based on city names. It's built using Express.js and Axios, with environment variable support via dotenv.

---

## 🧩 Features

- 🔍 Get current weather by city name
- 🌐 Integrates with [OpenWeatherMap](https://openweathermap.org/api)
- 🧪 Uses `.env` to manage API secrets securely
- ⚙️ Lightweight Express.js server
- 📦 Includes `axios`, `dotenv`, and `express` as dependencies

---

## 📁 Project Structure

```
weather-app/
├── public/             # Static frontend files (if needed)
├── .env                # API key configuration
├── .gitignore          # Ignored files for Git
├── server.js           # Express server logic
├── package.json        # Project metadata & dependencies
├── package-lock.json   # Locked dependency tree
└── README.md           # Documentation (You are here!)
```

---

## 🔧 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/daksh0601/weather-app.git
cd weather-app
```

2. **Install the dependencies**

```bash
npm install
```

3. **Configure your environment**

Create a `.env` file and add your OpenWeatherMap API key:

```env
API_KEY=your_api_key_here
```

> ⚠️ Never commit your `.env` file to GitHub. Make sure it’s in `.gitignore`.

4. **Start the server**

```bash
node server.js
```

5. **Use the weather API**

Visit:

```
http://localhost:3000/weather?city=London
```

Example response:

```json
{
  "name": "London",
  "main": {
    "temp": 15.0
  },
  "weather": [
    {
      "description": "clear sky"
    }
  ]
}
```

---

## 📚 Technologies Used

- **Node.js** – Runtime environment
- **Express** – Web server framework
- **Axios** – HTTP client for API calls
- **dotenv** – For managing environment variables

---
