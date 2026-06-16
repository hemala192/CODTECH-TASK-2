
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