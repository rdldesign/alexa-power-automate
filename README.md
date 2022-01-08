# Power Automate and Alexa
This is a demonstration of how to make a request to Microsoft Power Automate 
from an Alexa skill endpoint written in node.js.

This demo retrieve device address and returns a UPRN (unique
property reference number). This could be used to make queries to other systems.

# Author note
The author investigated the possibility of using Power Automate as the endpoint for the skill. 
Unfortunately when submitting the skill for review by Amazon it was rejected. After lookining
into the issue more the author realised that skill endpoint would need to

# How it works 

- The user asks 'What is my UPRN?'
- Alexa processes the intent and sends request to Power Automate
- A http trigger and passes the address to the flow
- A call is made to retrieve the UPRN

# Installation process
- Create new skill
- Upload skill custom endpoint js

# Resources

- [Postcodes.io](https://postcodes.io/) Free open source tool for extracting postcode data

# To do
- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley
