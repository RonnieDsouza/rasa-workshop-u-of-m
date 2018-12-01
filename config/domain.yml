domain_yml = """
intents:
  - greet
  - goodbye
  - mood_affirm
  - mood_deny
  - mood_great
  - mood_unhappy
  - printer_problem
  - printer_problem_deny

actions:
- utter_greet
- utter_cheer_up
- utter_did_that_help
- utter_happy
- utter_is_it_plugged_in
- utter_goodbye

templates:
  utter_greet:
  - text: "Hey! How are you?"

  utter_cheer_up:
  - text: "Here is something to cheer you up:"
    image: "https://i.imgur.com/nGF1K8f.jpg"

  utter_did_that_help:
  - text: "Did that help you?"
  
  utter_is_it_plugged_in:
   - text: "Is it plugged in boy?"
  
  utter_happy:
  - text: "Great carry on!"

  utter_goodbye:
  - text: "Bye"
"""
%store domain_yml > domain.yml

print("Done!")
