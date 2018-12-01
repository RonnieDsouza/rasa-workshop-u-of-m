stories_md = """


## printer problem path
* greet
 - utter_greet
* printer_problem
  - utter_is_it_plugged_in
* printer_problem_deny
  - utter_goodbye
  * printer_problem_deny
  - utter_disappointed
  - utter_goodbye
  
* confirm
  - utter_lies
  - utter_goodbye
  
## say goodbye
* goodbye
  - utter_goodbye
"""
%store stories_md > stories.md

print("Done!")
