# Commodity Futures and Weather Tracker

Graduate project for "CSIS 638 - Implementation of Database Management Systems" at the College of Charleston.

Project aims to visualize relationships between major agricultural commodities (corn, wheat, soybeans, rough rice, oats, coffee, cocoa, cotton, sugar, and orange juice) futures prices and a variety of weather measurements recorded from their corresponding major (top 3) regions of gloabl production. 

Financial data is sourced from Yahoo Finance API calls. 

Weather data is sourced from Open-Meteo API calls. 

Data pipeline is constructed with a connection to a MongoDB database with two collections: 'Commodities' and 'Weather'. 
