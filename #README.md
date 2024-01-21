# WoW SoD Random Raid Group Generator

## Functionality:
- Given a fixed group of classes/specs:
    - Randomly generate a raid group with 2 tanks, 2 healers and 6 dps

## v.0 Feature List:
- Input using Command Line Interface (CLI)
- User asks if they would like a raid group generated
    - An input of "Y" enables the program to run
    - An input of "N" cancels the app
- If input is "Y": 
    - Randomly generate a raid group with the following criteria:
        - 10 player max:
            - 2 classes have to be tanks
            - 2 classes have to be healers
            - 6 classes have to be dps
    - Generate raid group is output to the command line
- User is asked if they want another raid group generated


## Future features:

- UI to display everything
    - use a web framework (Flask/Django)?
- Optional parameters:
    - No two of the same class
    - No two of the same spec
    - No clothies/mail/leather etc.
- Pull in external data to make optimal raid groups based on parses or logs
