
# Gmail Scrapping
Hi, before we do the project, we need a short brief about the story behind it. 

Back in 2022, I was working in an Indian startup company where one of my chores was based on reading an automatic email that arrived every 30 minutes. If this email contained on his body a piece of information that was a number winch could be less or equal to 5, and in this case, I had to email another department to let them know that something wasn't right.

This kind of bullshit that gigant startups do and forget how to automate. 

So I decided to create this script to do this Chore by myself; keep in mind that back in that time, I didn't have much knowledge in Python, so forgive me if I used some weird or nonconventional stuff in my code.

The cool part of this coding is its remarkable ability to navigate through the Google Authentication M2F factor. 

But I must confess that I didn't craft the M2F factor piece of code. I owe a debt of gratitude to an anonymous hero from Stack Overflow. Unfortunately, their virtual trail has disappeared, but I want to give them a shout-out for their invaluable assistance. 

This project wouldn't have been the same without their expertise!


## Liberies
 - selenium
 - webdriver
 - time
 - sleep
 - Schedule
## Version
This was wrriten using Python 3 and Jupyter Noobok

## Script steps
To make a bit easier to undestand I will describe how the script suppost to work. 
   1. Open a chrome window and call the gmail page
   2. Log to your gmail inbox
   3. Pass by the google Autentication 
   4. Open the html verion of gmail inbox
   5. Read the email folder expected
   6. Analyze the email body
   6. Respond the email or close the page
   7. Trigger the schedule to run again after 31 minutes again

