# Demand Analysis for Shared Electric Bicycles in India: Exploring Influencing Factors and Recommendations for Service Optimization

## Business Problem and Dataset Description

> The "Yulu" dataset contains information about the demand for shared electric bicycles in India, provided by the leading Indian micromobility provider, Yulu. This company offers unique vehicles for daily trips aimed at alleviating traffic congestion in India and providing a safe, convenient, and affordable solution for transportation. Yulu zones are located in optimal places, including metro stations, bus stops, office spaces, residential areas, and corporate offices, to facilitate first and last-mile trips.

Recently, Yulu has faced significant revenue declines, prompting the company to seek assistance from a consulting firm to understand the factors influencing the demand for these shared electric bicycles, especially in the Indian market.

### Dataset Column Profile:

- **datetime**: Date and time collected hourly
- **season**: Season (1: spring, 2: summer, 3: autumn, 4: winter)
- **holiday**: Whether the day is a holiday (extracted from http://dchr.dc.gov/page/holiday-schedule)
- **workingday**: If the day is neither a weekend nor a holiday, it is marked as 1, otherwise 0.
- **weather**:
  1. Clear, Few clouds, Partly cloudy
  2. Fog + Cloudy, Fog + Broken clouds, Fog + Few clouds, Fog
  3. Light snow, Light rain + Thunderstorm + Scattered clouds, Light rain + Scattered clouds
  4. Heavy rain + Ice pellets + Thunderstorm + Fog, Snow + Fog
- **temp**: Temperature in degrees Celsius
- **atemp**: Perceived temperature in degrees Celsius
- **humidity**: Humidity
- **windspeed**: Wind speed
- **casual**: Number of casual users
- **registered**: Number of registered users
- **count**: Total number of bikes rented, including both casual and registered users
