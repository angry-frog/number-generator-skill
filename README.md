## RandomNumber skill
---

This skill picks a random number between 1 and 100

To get this done we need:

* to assign a variable to generate a random number

### Current state 
---

Working features:

* Picks random number between 1 and 100 and informs user


Known issues:

* on Picroft an error occurs after number spoken
* IOError: [Errno 13] Permission denied: '/opt/     mycroft/skills/random-number-skill/settings.json'

* as per troubleshooting.md in docs perform:

            cd /opt/mycroft/skills/
            sudo chown mycroft:mycroft -R number-generator-skill
  
TODO:

* fix Known issue so extra steps are not needed

* add feature to change number range through voice command

         “pick a number between 1 and 1000”
         “pick a number between 2 and 44”
         
### Usage
---
- PICK A NUMBER
