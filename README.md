# small-improvements
# stories
1) As a user, I want to verify if a specific route is available
2) As a system admin, I want to be able to handle (insert / delete / update routes) witihin the bus route file
3) As a system admin, I want to have a system that automatically refreshes itself everytime there's a change within the bus route file

# Acceptance Criterias
Given 2 station codes,
When a search is performed within the system,
Then I, as a user, want to know if they belong to the same route
Given a route file,
When as a System Admin I want to:
Insert a new Station, Then I want to see this new station retrieved from the search, without restarting my system
Delete an existing Station, Then I want to not see anymore this station retrieved from the search