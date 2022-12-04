# PUSH ISSUE

## Issue Summary 
On Sunday, November 13, 2022 at 3:00am (GMT+3) , Github.com wasn't accepting my push request for the AirBnB_V2 project. At its peak, this issue affected anly me from being able to complete this portion of the project in a respectable time frame. The root cause of the issue was Github.com recognizing a repository that was linked to a different individual at ALX.

## Timeline(all times Pacific Time)

* 9:00am (GMT+3)-Proper completion of pushing a file to github is completed
* 9:05am (GMT+3)-Issue detected after the ALX  checker return 
* 9:10am (GMT+3)-The user ensures that he has done the proper checks for the file
* 9:28am (GMT+3)-Following the Github.com documentation for fixing push and pull request, the user doesn't come up with a proper solution
* 9:32am (GMT+3)-The user asks other members of ALX peer to take a look at what is causing the issue
* 11:00am (GMT+3)-More students try to trouble shoot the problem but nothing was resolved
* 1:00pm (GMT+3)-The cause of the problem was found by me
* 1:05pm (GMLT+3)-The issue was Github referring to the original Airbnb repository of Abdelaziz Kassaw
* 3:00pm (GMT+3)-we fixed the issue by creating a entire new repo

### Root cause

At 1:00PM (GMT+3), a configuration change was made. The change specified that the current repo of user1 was linked to the repo of user2. Since the AirBnB project code base is linked to user2 and user1 originally collaborated with user2 at the beginning of the AirBnB project, Github didn't recognize the files eventhough they were pushed to user1's repository.

## Resolution

* At 3:00pm (GMT+3), a new repository was made and properly configured to be recognized by ALX. Create a new repository to avoid this issue
