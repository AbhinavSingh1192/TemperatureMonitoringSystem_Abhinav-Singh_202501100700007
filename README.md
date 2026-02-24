# TemperatureMonitoringSystem_Abhinav-Singh_202501100700007
Case Study Title: Temperature Monitoring System

Problem Statement:
1. Build a Python code to display messages according to the temperature received from an assumed IoT system.
2. Accept max and min limit temperature.
3. Generate random values for temperature at every 2 second interval.
4. Compare with the limits to display appropriate value.
Approach
Input Temperature Limits
Take minimum and maximum temperature values from the user using input().
Simulate IoT Temperature Data
Use random.uniform() to generate random temperature values.
Use round() to limit decimal places.
Continuous Monitoring
Use an infinite while True loop to keep monitoring.
Use time.sleep(2) to pause execution for 2 seconds between readings.
Comparison Logic
If temperature < minimum → Display "Below Minimum Limit"
If temperature > maximum → Display "Above Maximum Limit"
Otherwise → Display "Within Safe Limits"
Stop Condition
User can stop the program using Ctrl + C.
Sample Output 1 (Within Safe Range)
Enter minimum temperature limit: 15
Enter maximum temperature limit: 35

Temperature Monitoring System Started...

Current Temperature: 24.56 °C
Temperature is within safe limits.

Current Temperature: 30.12 °C
Temperature is within safe limits.
Sample Output 2 (Below Minimum Limit)
Enter minimum temperature limit: 10
Enter maximum temperature limit: 40

Temperature Monitoring System Started...

Current Temperature: 5.78 °C
Temperature is BELOW minimum limit!
Sample Output 3 (Above Maximum Limit)
Enter minimum temperature limit: 18
Enter maximum temperature limit: 32

Temperature Monitoring System Started...

Current Temperature: 41.23 °C
Temperature is ABOVE maximum limit!
