# COVID-19 Data Exploration

## Project Overview
This project explores COVID-19 data using SQL to analyze trends, infections, death rates, and vaccination progress. The dataset used includes records of COVID-19 deaths and vaccinations worldwide.

## Skills Demonstrated
- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Data Type Conversion

## Data Source
The project utilizes two tables:
- **CovidDeaths**: Contains COVID-19 case and death statistics.
- **CovidVaccinations**: Contains data on COVID-19 vaccinations.

## SQL Queries and Insights
### 1. Initial Data Exploration
- Extracts relevant columns from the `CovidDeaths` table, filtering out NULL continents.

### 2. Total Cases vs. Total Deaths
- Analyzes the likelihood of death if infected, specifically for Jamaica.

### 3. Total Cases vs. Population
- Calculates the percentage of the population that contracted COVID-19.

### 4. Highest Infection Rate per Population
- Identifies countries with the highest infection rate compared to their population.

### 5. Highest Death Count per Country
- Lists countries with the highest total deaths.

### 6. Highest Death Count per Continent
- Determines the continents with the highest COVID-19 death count.

### 7. Global Numbers Analysis
- Aggregates global total cases, deaths, and calculates the death percentage over time.

### 8. Population vs. Vaccinations
- Computes the rolling number of vaccinated people per location using:
  - **Joins**: Merging deaths and vaccination data.
  - **CTEs**: Storing rolling vaccination counts.
  - **Temporary Tables**: Similar calculation with stored temporary results.
  - **Views**: Storing the calculated results for future use.

## Key Findings
- The percentage of the population affected varies by country and continent.
- Some countries had extremely high infection and death rates relative to their population.
- Vaccination rollout analysis shows progressive increase in immunization.

