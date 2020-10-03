## search hospital hppy path
* greet
  - utter_greet
* search_provider{"facility_type":"hospital", "location":"San Francisco"}
  - action_facility_search
* thanks
  - utter_goodbye
  
  
## search hospital + location
* greet
  - utter_greet
* search_provider{"facility_type":"hospital"}
  - utter_ask_location
* inform{"location":"San Francisco"}
  - action_facility_search
* thanks 



## greeting
* greet
  - utter_greet

## intro
* corona_intro
  - utter_corona_intro

## novel
* novel_virus
  - utter_novel
  
## high risk
* high_risk
  - utter_risk

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
