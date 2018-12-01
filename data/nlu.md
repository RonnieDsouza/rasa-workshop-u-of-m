nlu_md = """
## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:affirm
- yes
- indeed
- of course
- correct

## intent:external_display_problem
- my tv doesn't work
- my monitor doesn't work
- 

## intent:printer_problem
- my printer is broken
- something wrong with my printer
- there seems to be an issue with my printer
- i'm having printer troubles

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really


## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good


"""
%store nlu_md > nlu.md

print("Done!")
