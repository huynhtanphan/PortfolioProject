#COVID-19 Data Analysis
This project involves analyzing COVID-19 data to gain insights into the spread and impact of the virus across different countries and continents. The data used in this project comes from two tables - CovidDeaths and CovidVaccinations - and is stored in a SQL Server database called PortfolioProject.

Dataset
The CovidDeaths table contains information about the total number of cases and deaths due to COVID-19 in different countries, while the CovidVaccinations table contains information about the number of people who have been vaccinated against the virus. Both tables have location and date as common columns, which are used to join the tables and create a combined dataset.

Queries
Several SQL queries were written to analyze the data and gain insights into the spread and impact of COVID-19 across different countries and continents. The following are some of the key queries used in this project:

Query 1: Selecting data from the CovidDeaths table, sorted by location and date.
Query 2: Looking at total cases vs total deaths to show the likelihood of dying if you contract COVID-19 in your country.
Query 3: Looking at total cases vs population to show what percentage of a population got COVID-19.
Query 4: Looking at countries with the highest infection rate compared to population.
Query 5: Looking at countries with the highest death count per population.
Query 6: Breaking things down by continent and showing continents with the highest death count per population.
Query 7: Looking at global numbers of total cases, total deaths, and death percentage.
Query 8: Using a Common Table Expression (CTE) to calculate the vaccination rate of a population.
Query 9: Using a temp table to calculate the vaccination rate of a population.
Query 10: Creating a view to store data for later visualizations.
