#  Mahiḷā surakṣatā eccarike - MSE
## A safety App for women under threat

MSE is an android application that helps a lady under threat to get support  from the police or other services immediately with the help of an automated emergency message/call which will be made when a lady screams loudly holding the phone with the app running in the background. 
### Steps
1. Scream recognition
2. GPS Information Extraction
3. Intimation to nearby Police Stations


## Tech stack used in our proposed solution
Android Application using Java 

## What's our idea?

When a woman feels insecure, she can turn on the app then the app starts running in the background. When the app detects a real panic scream, then the information about the her location will be sent immediately to the nearby police stations. So, she can get an immediate help from the police.

## How does the app work at this stage?

1. Record the input voice 
2. Send GPS information immediately to the contact number mentioned in MapsActivity.java. As of now a sample contact number is used for testing the app.Later it can be changed to the police station number.

## What work do we still need to do?

1. Real panic scream vs non-panic scream classification
2. Provide immediate support after recognising words similar to "help" in different languages.
