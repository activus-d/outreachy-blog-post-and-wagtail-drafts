# Users status
A Wagtail user can either be active or inactive. A user is active if he has the right permissions to perform any action in the Admin interface.
The status of a user determines whether that user still has the right permission to perform any action in the Admin interface. Wagtail provides for two statuses; active status and inactive status.

## Active status
A user is active if they have the right permissions to access the Admin interface and perform an action. This action could be as simple as making a draft.

## Inactive status
When a user loses access to the Admin interface, they become inactive. Changing the status of a user from active to inactive is one of the rights reserved exclusively to an Administrator.
Making a user inactive could be a reasonable alternative to deleting the user. This is because if you delete a user, you lose all the records or history of all actions that such a user has performed in the past. This might lead to some inconvenience. By making such users inactive instead, you deny them their access to the Admin interface while preserving the records of their actions while they were active.