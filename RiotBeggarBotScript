#!/usr/bin/env python
import sys
import random
from twython import Twython

playValorantID = "1230550898616586242"

#Opens file and reads in Twitter Consumer and Access Information

with open("KeyTokenSecrets.txt") as file:
    confidential = file.readlines()
    confidential = [line.rstrip() for line in confidential]
file.close()

#Stores confidential information in easily-readable variables for later use

CONSUMER_KEY = confidential[0]
CONSUMER_SECRET = confidential[1]

ACCESS_TOKEN = confidential[2]
ACCESS_SECRET = confidential[3]

#Creates api object with the information stored

api = Twython(CONSUMER_KEY , CONSUMER_SECRET , ACCESS_TOKEN , ACCESS_SECRET)

with open("DMsList.txt", "r+") as file:
    allDMs = file.readlines()
    twitterDM = allDMs[0]
    file.seek(0)
    file.writelines(allDMs[1:])
    file.write(twitterDM)
file.close()

api.send_direct_message(event = {"type": "message_create",
    "message_create":{"target": {"recipient_id": playValorantID},
    "message_data":
    {"text": twitterDM}}})
