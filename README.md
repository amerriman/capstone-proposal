# InsureSafe

## Summary

- An app that would help users keep track of personal property items for an insurance claim


## technologies

- MEAN Stack
 - Express
 - Angular
 - Unsure about database at this point - will need to frame out if it makes more sense to use MongoDB or PSQL
 - Node.js
- Gulp
- Mocha/Chai testing
- Bootstrap

### APIs

- Sendgrid - for sending email reminders
- (Maybe Twilio also)


## MVP

- Users will be able to login (with an email and password OR through Google)
- Users will be able to create a directory of personal property for insurance documentation - would include brand, serial numbers, cost, date of purchase, and uploads of photos or receipts if they have them
- Users would be emailed on key dates (holidays, birthday) to prompt for updating
- Users could log in and delete or update their items


## Additional features

- User-friendly and responsive UI
- Email reminders to user for updating their info

## Stretch Goals

- Users could print a PDF of their items
- Users could search for item cost using Amazon API if I can figure out how to use that...
- Users would be able to select items by room and be given a general cost of replacement (ie - I have a couch and a dining table and two armchairs and a television - total replacement cost could be in $x-$y range)



#Congress Watcher

## Summary

- Site that would provide visual information for users about members of the House and Senate.


## technologies

- MEAN Stack
 - Express
 - Angular
 - MongoDB
 - Node.js
- Gulp
- Mocha/Chai testing
- NVD3 for visuals
- Bootstrap

### APIs

- Sendgrid (maybe - so users could send emails directly to reps)


## MVP

- Users will be able to see current and past members of the House and Senate - along with what committees they are on, contact info and voting trends.
- Utilize charts to compare Democratic and Republican support for specific bills
- Utilize charts to compare two members voting trends
- Users can login and save their local reps to their own dashboard account for easier access to their contact information


## Additional features

- User-friendly and responsive UI


## Stretch Goals

- Create a data map of some type


# Write Smart

## Summary

- An app that would help teachers and students evaluate the sentiment of their own writing, or another author's writing.


## technologies

- MEAN Stack
 - Express
 - Angular
 - Unsure about database at this point - will need to frame out if it makes more sense to use MongoDB or PSQL
 - Node.js
- Gulp
- Mocha/Chai testing
- Bootstrap
- nvd3

### APIs

- Watson Sentiment analysis


## MVP

- Users can test the application without having to login
- Teachers can create accounts that will be linked to their students, and vice versa
- Users will input text and the application will return a sentiment analysis with keywords that are rated with 'positive' or 'negative' sentiment.
- text will be stored, along with keywords, in user accounts
- Users can see data related to their text - presented as an infographic, with charts, graphs, etc.


## Additional features

- User-friendly and responsive UI


## Stretch Goals

- Users could print a PDF of their items
- Word cloud generator with keywords

