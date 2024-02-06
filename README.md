1)
The app is designed to hold a database of coding-related events, to allow people to browse for events that they might be interested in attending.

2)
The app currently allows for the creation of events, event categories, and tags. Information is stored in a mySQL database.
There is search functionality to view events currently stored in the database baed on certain search criteria.

3)
Future improvements. Add a "Person" class, which will allow individuals to create an account.
Users with accounts will be able to add new events, event categories, or tags to the database.
Users can also register for events that they are interested in attending.
User profiles will maintain records of past attended events and upcoming events for which they are registered.
Event classes will be updated to maintain a record of users in attendance at past events, to allow users to view other users from events and network with them.

Person Class:
id, int (auto-generated)
name, string
username, string
password, string

Constructors, getters, and setters

User Profile Class
PastEvents - List
FutureEvents - List
Created Events - List
Created Event Categories - List
Created Tags - List
