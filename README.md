# Starbucks Capstone Project
This project was done as part of the requirements for Udacity Data Scientist Nanodegree

## Table of Content
1. Project Overview
2. Project Motivation
3. Data Description
4. Conclusion
5. Author, and Acknowledgement

## Project Overview
The data set for this project was provided by Udacity. The program used to create the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.
Each person in the simulation has some hidden traits that influence their purchasing patterns and are associated with their observable traits. People produce various events, including receiving offers, opening offers, and making purchases.

## Project Motivation
This project analysis was done to identify the categories of consumers that are most responsive to the various types of offer, and build a recommendation engine that best presents each type of offer.

## Data Description
1. profile.json: Rewards program users (17000 users x 5 fields)
- gender: (categorical) M, F, O, or null
- age: (numeric) missing value encoded as 118
- id: (string/hash)
- became_member_on: (date) format YYYYMMDD
- income: (numeric)

2. portfolio.json: Offers sent during 30-day test period (10 offers x 6 fields)
- reward: (numeric) money awarded for the amount spent
- channels: (list) web, email, mobile, social
- difficulty: (numeric) money required to be spent to receive reward
- duration: (numeric) time for offer to be open, in days
- offer_type: (string) bogo, discount, informational
- id: (string/hash)

3. transcript.json: Event log (306648 events x 4 fields)
- person: (string/hash)
- event: (string) offer received, offer viewed, transaction, offer completed
- value: (dictionary) different values depending on event type
- offer id: (string/hash) not associated with any "transaction"
- amount: (numeric) money spent in "transaction"
- reward: (numeric) money gained from "offer completed"
- time: (numeric) hours after start of test

## Conclusions
The result of the analysis and the analysis report for this project can be found on this [Medium post](https://obisanoluwatosin.medium.com/starbucks-irresistible-discount-offers-dcc5da01856a).

## Author, and Acknowledgement
* Oluwatosin (Tosin) Obisan
* All credits to Udacity for providing the data set for this project.
