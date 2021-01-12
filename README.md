# MailServerProject
Mail Server Project 


### Description and features

- We made a mail server like a Gmail which you can make an account
on it and communicate with other people by sending and receiving
emails, attachments, images from them.
- The user login in with our mail, if he has an account he will sign in, if
he has not an account he will sign up and his information will be saved
as email, password and his name.
- The first page which will appear to him is a frame that contains all
features like send mails or view inbox, draft, trash, contacts, details,
sign out.
- If he wants to send emails he will press on compose to send emails,
attachments or images. He enters the email of the person he would
send to him, enters subject of the sent mail and upload the mail that he
wants to send.
- If you wants to discard the message it will not sent but will be put in
the Drafts.
- If the person who made the account wants to delete emails from his
own, he will delete it and it will be put in the trash folders.
- If the person who made the email wants to see the sent mails which
he sent, he will press on the sent to see them.
- The person could search on emails with any words he remember from
email.


### Bonus parts


- We assume that all users have one or two accounts and there is all
features of any mail app like send mails or receive emails or send
attachments.
- When you open the application you are required to enter your email
and password and if you don't have an email you should enter sign up
button to make a new account.
- Each user will have a file called "info.txt" in folder user, this file
contains his data.
- We assume that the user when Compose a message to any user. he
should enter: the mail, subject, data, priority & attachments.
- The user does not insert a subject for his message to will be recorded
as " ", and the user does not insert a priority for his message to will be
recorded as 0.
- If the user wants to delete a message from his, he should choose the
message and delete one by one or make multi select.
- The user can filter the messages by subject or name or date.
- We assumed that the user may want to log out from his mail so we
provide a Log out Button.


### Data Structure usage

- We use stack, priority queue.
- Doubly Linked list used for reading from files,displaying on GUI.


### Algorithms

- Sign in:

This function check for right email and pass and give access if that right
For all mails in the file
If mail is right
Check for password
If password is write
Go to home page
Else
Back to sign in

- Sign up:

This function makes an account in the mail but
Firstly take all input from a text field
Check that all is right
For all signed emails
If this name not exist)
Make account
Else

The account is exist and return to sign in


### Main module of your program

- inbox:

contains user's received messages.

- Sent Mails:

contains user's sent messages.

- Compose:

Helps user to send emails to other people.

- Drafts:

contains user's wrong messages which had errors.

- Details:

contains user's information.

- Contacts:

contains user's sent and received emails which he communicates with them.

- sign out:

Help user to log out from the mail.

- Trash:

Contains deleted messages.


### User Manual

- The user enters the email, if he has an email he will press on sign in to
log in his email account, if he has not an email account he will press on
sign up to make an account and to login the email account.
- The Compose, Sent Mails, Details, Sign out, Drafts, Trash and Inbox.
All of these items will appear to the user when he enters the mail
- If he wants to send an email he will press on compose button to send
email by entering to whom he would send, subject of the sent email,
Data of the email and the email he wants to send (attachment, image,
......etc).
- If the person wants to delete an email he would press on delete
button and it will be sent to the trash folder.
- If the user entered wrong email name while sending to another user
or there is any error happened while sending email, this email will be
sent to the Drafts folder.
- If he wants to find contacts which he sent to them emails or received
from them emails, he will press on contact button and it will appear to
him contacts' emails which he sent or received from them emails. If he
presses on one of these accounts which appeared to him it will go to
the compose to help him to send emails.
- If the user wants to logout from the mail he will press on the Signout
button to logout.
- He could search emails depending on any word.
- He could sort emails depending on name, subject, date.
- He could refresh the page to have new notifications which happened.
