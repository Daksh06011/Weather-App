🌦️ Weather App — Real-Time Weather with Node.js & Express
This is a simple and lightweight Node.js weather application that uses the OpenWeatherMap API to fetch real-time weather data based on city names. It's built using Express.js and Axios, with environment variable support via dotenv.

🧩 Features
🔍 Get current weather by city name

🌐 Integrates with OpenWeatherMap

🧪 Uses .env to manage API secrets securely

⚙️ Lightweight Express.js server

📦 Includes axios, dotenv, and express as dependencies

📁 Project Structure
bash
Copy
Edit
weather-app/
├── public/             # Static frontend files (if needed)
├── .env                # API key configuration
├── .gitignore          # Ignored files for Git
├── server.js           # Express server logic
├── package.json        # Project metadata & dependencies
├── package-lock.json   # Locked dependency tree
└── README.md           # Documentation (You are here!)
🔧 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/weather-app.git
cd weather-app
Install the dependencies

bash
Copy
Edit
npm install
Configure your environment

Create a .env file and add your OpenWeatherMap API key:

env
Copy
Edit
API_KEY=your_api_key_here
⚠️ Never commit your .env file to GitHub. Make sure it’s in .gitignore.

Start the server

bash
Copy
Edit
node server.js
Use the weather API

Visit:

bash
Copy
Edit
http://localhost:3000/weather?city=London
Response:

json
Copy
Edit
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
📚 Technologies Used
Node.js – Runtime environment

Express – Web server framework

Axios – HTTP client for API calls

dotenv – For managing environment variables
