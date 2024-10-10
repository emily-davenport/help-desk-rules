# Help Desk Rules
***"Remember this is a family restaurant"***

## Overview
I want to make a bot for our Google Chat at the Help Desk which will cite infractions of our "Help Desk Rules" which can be [found here](https://docs.google.com/spreadsheets/d/1U2-3ZvXdyjR2v7_pV8a9iDZVZPiSv0bGeapQZ6BZa9E/edit?gid=0#gid=0)

## (Future) Features
* Will cite infractions of Help Desk Rules like so:
  > John Doe: I'm throwing things as the help desk!
  > 
  > Help Desk Rule Bot: \[RULE INFRACTION DETECTED\]
  > Rule: "No throwing at the help desk"
  > This is John Doe's 5th infraction.
* Can issue reminders for things categorized as "Overall Suggestions" (can be disabled in config):
  > Help Desk Rule Bot: "Remember this is a family restaurant"
* Can be disabled with a !mute command if the messages are too disruptive. Usage: !mute \<time to mute in minutes\>
