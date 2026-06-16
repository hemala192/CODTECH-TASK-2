
CODETECH TASK-2
# Weather Data Scraper and Analyzer

# Sample weather data
days = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"]
temperature = [32, 30, 35, 31, 33]
humidity = [70, 65, 75, 68, 72]

# Display weather data
print("Weather Report")
print("----------------")
for i in range(len(days)):
    print(days[i])
    print("Temperature:", temperature[i], "°C")
    print("Humidity:", humidity[i], "%")
    print()

# Analyze data
highest_temp = max(temperature)
lowest_temp = min(temperature)
average_temp = sum(temperature) / len(temperature)

print("Weather Analysis")
print("----------------")
print("Highest Temperature:", highest_temp, "°C")
print("Lowest Temperature:", lowest_temp, "°C")
print("Average Temperature:", average_temp, "°C")

DESCRIPTION:
🎯 Objective

To collect real-time weather data from online sources, process it, and analyze weather patterns to understand temperature, humidity, and weather trends.

 🛠️ Technologies Used

* Python
* Requests (for web data fetching)
* BeautifulSoup (for web scraping)
* Pandas (for data handling)
* Matplotlib / Seaborn (for visualization)

📌 Key Features / Objectives

* Scrape weather data from websites or APIs
* Clean and organize raw weather data
* Analyze temperature and humidity trends
* Visualize weather patterns using graphs
* Provide simple insights from data

 Simple Python Idea :

* Fetch weather data from a website/API
* Store it in a structured format (like CSV or DataFrame)
* Perform basic analysis (average temp, max/min values)
* Display results using charts


 📊 Outcome

This project helps understand how weather data changes over time and builds skills in web scraping, data analysis, and visualization.