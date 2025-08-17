# REST API Practice with OpenWeatherMap / REST-API Praxis mit OpenWeatherMap

## Overview / Übersicht
This repository contains a **hands-on practice project** for working with REST APIs in Python, specifically using the **OpenWeatherMap API**.  
Dieses Repository enthält ein **praktisches Übungsprojekt**, um mit REST-APIs in Python zu arbeiten, speziell mit der **OpenWeatherMap API**.

The [Jupyter notebook](openweather_api.ipynb) includes:
- Fetching weather data for multiple cities using **GET requests**  
- Loading the **API key** from a file securely  
- Handling **JSON responses** and exploring their structure  
- Converting JSON data into **pandas DataFrames**  
- (Optional) Saving data as **CSV** or **JSON**  
- Explanation of **common REST API methods**: GET, POST, PUT, PATCH, DELETE 

Das [Jupyter-Notebook](openweather_api.ipynb) enthält:
- Abrufen von Wetterdaten für mehrere Städte mit **GET-Anfragen**  
- Sicheres Laden des **API-Schlüssels** aus einer Datei  
- Verarbeitung und Analyse von **JSON-Antworten**  
- Umwandlung von JSON-Daten in **pandas DataFrames**  
- (Optional) Speichern der Daten als **CSV** oder **JSON**  
- Erklärung zu **REST-API-Methoden**: GET, POST, PUT, PATCH, DELETE 

### 2. Obtain your OpenWeatherMap API key / OpenWeatherMap API-Schlüssel erhalten
Before using the notebook, you need to **register for a free account** at OpenWeatherMap and get your API key.  
Bevor Sie das Notebook verwenden, müssen Sie sich **für ein kostenloses Konto** bei OpenWeatherMap registrieren und Ihren API-Schlüssel erhalten.

Steps / Schritte:
1. Sign up at [OpenWeatherMap](https://openweathermap.org/)  
   Bei OpenWeatherMap registrieren
2. Copy your **API key** and save it in a file (e.g., `_api_keys/openweather.txt`)  
   Ihren **API-Schlüssel** kopieren und in einer Datei speichern (z. B. `_api_keys/openweather.txt`)