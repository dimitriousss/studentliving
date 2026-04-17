# Warsaw Student Housing Analytics Project

## Data analytics project exploring student housing availability, affordability, and location trade-offs using real estate listings and geospatial data. The project combines data scraping, geospatial analysis, and scoring models to identify key market gaps and optimize apartment selection for students.

## Problem
#### Today, finding good student housing in Warsaw is difficult due to high prices, poor visibility into location-based advantages and amount of misleading information in the listings.

## Insights
#### - Ambiguity of "rooms" parameter and real area-rooms relationship, > 50% of the "2-room appartments" are not shareable
#### - Fewer than 2% of flats < 40m² fall within an affordable budget range for student renting
#### - Księcia Janusza, Młociny are great non-central locations with many appartmments suitable for solo student living
#### - 2-room > 50m² flat sharing is a beneficial strategy for students in Warsaw, rated ~17% higher than solo flats on average
#### - More than half of university catchment hexes have inadequate private rental supply, only ~8% is covered by dorms

## Approach
#### 1) Data extraction (OpenStreeetMap, otodom.pl scraping)
#### 2) Dataset creation (data cleaning, feature engineering, splitting the analysis between solo and shareable flats)
#### 3) Student liveability score
#### 4) Flat sharing strategy analysis
#### 5) Housing supply gap analysis
#### 6) Personalized student liveability scoring engine / flat reccommendation tool

## Output
#### - Geospatial infographic maps
#### - Apartment ranking system
#### - Student-oriented recommendation tool
