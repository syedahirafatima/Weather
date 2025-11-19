# Weather.py

A simple Python script that fetches real-time weather information for any city using the `wttr.in` API.

## 📌 Features

* Get current weather conditions and temperature instantly.
* Uses the free public weather service `wttr.in`.
* Minimal and easy-to-understand code.


## 🚀 How It Works

The script sends a request to:

```
<https://wttr.in/><city>?format=%C+%t

```

This returns a short weather summary containing the condition and temperature.
## 📂 File

- [weather.py](http://weather.py/): Main script that fetches and prints the weather.
## 🛠️ Requirements

Make sure you have the `requests` library installed:

```bash
pip install requests

```

## ▶️ Usage
Run the script in your terminal:

```bash
python weather.py
```

Enter the city name when prompted:

```
Enter city name: London
```

Output example:

```
Partly cloudy +10°C
```
## ⚠️ Notes

- You need an active internet connection.
- If the API cannot fetch data, the script returns:
