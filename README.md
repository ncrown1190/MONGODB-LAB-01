# MONGODB-LAB-01
Setup: Load this data//https://gist.github.com/dwolverton/59222c7148f9dbe62b68478981d8f190 //for a people collection into your MongoDB database. You can copy-paste the contents into MongoDB shell and run it. The documents in this collection look like this:
{ "first_name": "Patricia",
  "last_name": "Medina",
  "email": "pmedina@trellian.com",
  "gender": "Female",
  "age": 36,
  "state": "Arizona",
  "children": [
    {"name": "Antonio", "age": 9},
    {"name": "George", "age": 13},
    {"name": "Kathy", "age": 16}
  ] }

Build Specifications:
Write MongoDB shell commands to do the following tasks. Record these commands in a text document and submit the document. You do not need to record the results of the commands.
Note: the numbers in parenthesis indicate the number of results to expect.

List all people. (200)
Count all people. (200)
List all people in Arizona. (6)
List all males in Arizona. (2)
List all people in Arizona plus New Mexico. (8)
List all people under age 40. (90)
List all females in Florida between the ages of 40 and 45 (inclusive). (4)
List people whose first name starts with "H". (2)
List all people in Michigan, sorted by first name. (6)
List all people who live in Virginia or are named Virginia.
List the names of people under age 30. Only display their first and last name. (38)
List all people in Montana. Display all information except age. (2)
List the email addresses of people with a ".edu" email. Only display the email. (12)

Extended Challenges:
Count all people with at least one child under age four. (69)
List people who have no children. (43)
List people who have at least one child. (157)
