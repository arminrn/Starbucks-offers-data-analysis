# Starbucks-offers-data-analysis

# Description

# Libraries

# Files


# Data

*profile.json*


gender: (categorical) M, F, O, or null

age: (numeric) missing value encoded as 118

id: (string/hash)

became_member_on: (date) format YYYYMMDD

income: (numeric)


*portfolio.json*


reward: (numeric) money awarded for the amount spent

channels: (list) web, email, mobile, social

difficulty: (numeric) money required to be spent to receive reward

duration: (numeric) time for offer to be open, in days

offer_type: (string) bogo, discount, informational

id: (string/hash)

*transcript.json*


Event log (306648 events x 4 fields)

person: (string/hash)

event: (string) offer received, offer viewed, transaction, offer completed

value: (dictionary) different values depending on event type

offer id: (string/hash) not associated with any "transaction"

amount: (numeric) money spent in "transaction"

reward: (numeric) money gained from "offer completed"

time: (numeric) hours after start of test

# Acknowledgements

Data is provided by Udacity and Starbucks
