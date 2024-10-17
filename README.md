# Real-Time-Data-Processing-System-for-Weather-Monitoring-with-Rollups-and-Aggregates

The Real-Time Data Processing System for Weather Monitoring is designed to continuously track and analyze weather conditions across major metropolitan areas in India, utilizing data sourced from the OpenWeatherMap API. The system aims to provide users with summarized insights into daily weather patterns through rollups and aggregates, while also enabling alerting mechanisms for critical weather thresholds.

#### Key Features:

1. **Data Retrieval**: The system fetches real-time weather data at configurable intervals (e.g., every 5 minutes) for cities such as Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad. It captures key parameters, including main weather conditions, current and perceived temperatures, and timestamps of updates.

2. **Temperature Conversion**: It automatically converts temperature readings from Kelvin to Celsius (or Fahrenheit), based on user preferences, ensuring the data is accessible and user-friendly.

3. **Daily Weather Summary**: The system rolls up weather data daily, calculating aggregates such as average, maximum, and minimum temperatures. It identifies the dominant weather condition, which is determined by the most frequently reported state, providing valuable context for understanding daily weather trends.

4. **Alerting Thresholds**: Users can define thresholds for specific weather parameters, such as high temperatures or particular weather conditions. The system continuously monitors incoming data and triggers alerts when thresholds are breached, enhancing user awareness and safety.

5. **Visualizations**: The application includes visual tools to display daily weather summaries, historical trends, and alerts, facilitating easy comprehension of complex data patterns and aiding in decision-making.

#### Testing and Validation:
The system is rigorously tested to ensure reliability, including checks for successful API connections, accurate data retrieval, temperature conversion, correct calculation of daily summaries, and effective alert triggering. 
