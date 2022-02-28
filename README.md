# Amazon_Vine_Analysis

## Overview
Is there a bias in Amazon Vine program reviews? We compared Amazon reviews written by members of the Amazon Vine program to ordinary reviews written by non-Vine users to see if there is a difference. 

For our study, we selected sports goods as the subject. 

## Tech and Process

We used pySpark to generate dataframes from the review information. Then we set up an RDS database and linked it to pgAdmin, then loaded the tables into this postgreSQL table. Following that, it was simple in pySpark to group the reviews into Vine / Not Vine and count them while computing a mean score.

## Results

Vine critics may be negatively biased or skewed, according to 42% of Vine program evaluations that received 5 stars and 53 percent of neutral reviews that got 5 stars. 

This result is specific only to the sports category of goods sold on Amazon.

## Summary
Vine critics may be negatively biased or skewed, according to 42% of Vine program evaluations that received 5 stars and 53 percent of neutral reviews that got 5 stars. 

This result is specific only to the sports category of goods sold on Amazon and, quite frankly, went against my personal hypothesis.

Further analysis on each category is recommended. There may be context behind certain product categories that show a bias over others.