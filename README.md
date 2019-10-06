# autopycon
An automatic crawler-scraper which will keep the users updated about CFP dates and deadlines. 

The premise of the script is to base all the updates based on twitter handles of the official Pycon accounts and periodically scrape them to update the database and intimate the subscribers about the CFP and deadlines so that they don't have to keep checking a website and add all these to their calendars. 

Contributions, Feedback, Thoughts etc. are welcome!

## Steps:
- Build a basic twitter scraper which, given a username can extract all the public tweets and associate metadata.
- Formulate rules to filter/identify if a tweet points to CFP(simple word lookup to begin with and gradually move to a language model maybe)
- Figure out a way to understand deadlines and extract dates(or extrapolate based on the date of tweet and compute deadline)
- Maintain a master db with Pycon X Year which will make sure users are not intimated more than once.
- Build a web app and add basic functionality(subscription)
- Let a user add a twitter handle to inspect.

## Updates: 

