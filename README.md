# B0UNC3
Sinatra and Ruby app that monitors users' mentions and automatically mutes accounts based on words or phrases listed by user.

## Summary
Users can input words and phrases that act as triggers, and my code manually monitors their mentions and automatically mutes accounts that use those words or phrases. The accounts (and tweets) are muted before they reach the user's timeline, and the user never has to see them!  In the case that the app accidentally muted the user's friends, the user can periodically check their profile for a list of people and tweets muted and choose to unmute their friends.

## Conclusion
I coded this project in 24 hours and intended to continue the work. However, two days after I started this project, [Twitter released their own monitoring capabilities](http://www.socialmediatoday.com/social-networks/twitter-adds-new-mute-words-tool-new-processes-combat-platform-abuse) and added the ability to mute single tweets to their API (versus muting an entire account). Very coincidental timing, but a victory for Twitter users.

## Instructions
The app automatically signs you into your Twitter account when you visit the home page.
![Homepage View](readme-assets/homepage.png)
* Pull down the code and input your own Twitter access tokens and consumer keys.
* Locally run the code and input blocked phrases or words, separated by commas.
![Word Input View](readme-assets/input.png)
* Scan your mentions for those words, and blocked tweets and accounts section of your profile will auto-populate.
![Profile Page View](readme-assets/blocked.png)
* Code that will actually mute users is commented out.
