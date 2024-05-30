
# Weather Conditions Flask App

This is a simple Flask application that allows users to enter a city name and get the current weather conditions.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nyarko-i/WeatherApp
   cd WeatherApp
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your API key:**
   - Register for an API key from [OpenWeatherMap](https://openweathermap.org/).
   - Create a `.env` file in the project root directory and add your API key:
     ```
     WEATHER_API_KEY=your_api_key_here
     ```

## Usage

1. **Run the Flask application:**
   ```bash
   flask run
   ```

2. **Open your browser and go to:**
   ```
   http://127.0.0.1:5000/
   ```

3. **Enter a city name and click "Submit" to get the weather conditions.**



## Live Demo

You can see the live demo of the application [here](https://weatherapp-zsao.onrender.com/).

