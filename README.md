# Virtual Realtor

Voice-enabled dialogue assistant for finding housing/apartments.


This system,
* Interacts with the user via a voice-enabled interface.
* Performs named entity recognition (NER) using Flair to find user's requirements.
* Finds the housing/apartment matches using real estate data from the Redfin database. (Using Python-Redfin is a Python wrapper for Redfin’s API.) 
* Display the matching houses/apartments along with location, price, bedrooms, bathrooms, and year built

## Instruction
1. Install requirements
```commandline
pip install -r requirements.txt
```

2. Run main.py file
```commandline
python main.py
```
