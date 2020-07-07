## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## intro
* greet
- utter_greet
* corona_intro
- utter_intro

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
