stories_md = """
## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* mood_affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* mood_deny
  - utter_goodbye

## printer problem path
* greet
 - utter_greet
* printer_problem
  - utter_is_it_plugged_in
* printer_problem_deny
  - utter_goodbye
  
## say goodbye
* goodbye
  - utter_goodbye
"""
%store stories_md > stories.md

print("Done!")
