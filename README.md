# voiceAssistant
A voice assistant for windows similar to Cortana, Siri and Google Voice Assistant. The voice assistant can perform the following funictions:
1. Send Emails through voice.
2. Tells date time when asked.
3. Wishes the the user when we run the program and asks "how may I help you?"
4. Can open websites (Google, StackOverflow, Youtube)
5. Can search wikipidiea.

## Send Email:
To send an email, we need to import a module called smtplib.

What is smtplib?

  Simple Mail Transfer Protocol (SMTP) is a protocol that allows us to send emails and route emails between mail servers. An instance method called sendmail is present in the SMTP module. This instance method allows us to send an email.  It takes 3 parameters:
    The sender: Email address of the sender.
    The receiver: T Email of the receiver.
    The message: A string message which needs to be sent to one or more than one recipient.
    
### User says "sends email" which truggers the send email function and then assistant asks user "what should I say" the user says the message. 

![Test Image 4](https://github.com/CallMeHarsh/voiceAssistant/blob/main/images/email%20I.png?raw=true)

### If there are are no errors then assistan will say "mail is sent successfully"

![Test Image 4](https://github.com/CallMeHarsh/voiceAssistant/blob/main/images/email%20O.png?raw=true)

## Date and time:
When assistant catches the key word "the time" in query, it tells the date and time. We are using the datetime() function and storing the current or live system time into a variable called strTime. After storing the time in strTime, we are passing this variable as an argument in speak function. Now, the time string will be converted into speech.

![Test Image 4](![image](https://user-images.githubusercontent.com/64908520/143187918-3b577031-2115-42f1-88dd-196112df76a9.png)

## As soon as the program runs, the assistant wishes the user, wishMe() function is triggered automatically.

## Opening websites
The assistant recognises the key words "open (website name)" and opens the website.
![image](https://github.com/CallMeHarsh/voiceAssistant/blob/main/images/website%20i.png?raw=true)
![image](https://github.com/CallMeHarsh/voiceAssistant/blob/main/images/website%20O.png?raw=true)



