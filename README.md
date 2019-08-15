# BinIt
A smart way to handle waste management. This repository contains files for a garbage monitoring program that will alert users to when the bin is full by text message, while continuously collecting usage data.

- Ultrasonic sensors interfaced with a Raspberry Pi handle data collection of how full a given trash can is
- Data is processed with Pandas and recorded in text form (CSV/Excel doc). If a particular threshold is reached, an alert is fired off    
- Twilio API was used to handle sending text messages to employees working for a city when a full garbage can is sensed</li>
- The trash cans/dumpsters that fill more frequently get emptied more frequently and vise versa. Data that is collected can be used to improve waste management routes longterm as well
