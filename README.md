# Hotel Recommendation System

## Overview
This project implements a personalized hotel recommendation system based on Expedia’s user data. The goal is to predict which hotel clusters users are most likely to book based on their search history, destination preferences, and previous interactions with the website. This recommendation system uses historical booking data, user preferences, and hotel features to provide tailored hotel suggestions.

## Data
The dataset consists of a random selection of user search events from Expedia. Each event includes information such as:

* user_id: Identifier for the user
* srch_destination_id: The destination selected by the user
* is_booking: Whether the user made a booking (boolean)
* hotel_cluster: The hotel group (cluster) that the user interacted with (booked or clicked on)

## Project Workflow
1. Data Loading and Preprocessing
2. Aggregation of Bookings and Clicks
3. Relevance Calculation
4. Merging with Latent Features
5. User Profile Creation
6. Similarity Calculation
7. Generating Recommendations
8. Output Top Recommendations
   
