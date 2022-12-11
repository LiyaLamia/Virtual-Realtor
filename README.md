# Virtual-Realtor
Voice-enabled dialogue assistant for finding housing/apartments.

This system,
  1. Interacts with the user via a voice-enabled interface.
  2. Performs named entity recognition (NER) using Flair to find user's requirements.
  3. Finds the housing/apartment matches using real estate data from the Redfin database. (Using Python-Redfin is a Python wrapper for Redfin’s API.)
  4. Display the matching houses/apartments along with location, price, bedrooms, bathrooms, and year built
