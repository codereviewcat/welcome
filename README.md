welcome
=======

A repository to welcome CodeReviewApp users


Welcome Aboard beta testers
===========================

Thanks for taking the time to test CodeReview. The current version is fairly limited but here are some of the things you can do:

**Add a GitHub account**: If you are reading this you've probably added an account already. If you have more than one account, feel free to add it. CodeReview is designed to work with multiple GitHub accounts at the same time.

**Refreshed your Feed**: Pull down on your feed to get updates to all your pull requests.

**Refresh an individual pull request**: If you are reading the activity of a pull request you can pull down to refresh that individual pull request.

**Use and view Markdown in comments**: Comments support full markdown and should have all the features of GitHub's markdown. Task lists, emoticons, and most importantly animated GIFs all work.

**See activity and changes**: When looking at pull requests you can toggle between the pull request's activity (comments/commits) and changes (the diff) using the tabs in the top right hand corner.

**Comment on pull requests**: On the activity view there is a comment bar down the bottom. Tap that to comment on the current pull request.

**Reply to review comments**: On the activity view if you see a review comment (a comment on a line of code) you can comment on it by tapping the reply text box.

**View individual commits**: Tap a commits hash to view the changes for that individual commit.

**Go full screen**: In landscape mode use a two finger spread gesture on the activity or changes view to make it full screen. Use a pinch gesture to return to non-full screen.


Missing Features and Known Bugs
===============================

I bet all that stuff sounds great. Well good news / bad news. Everything listed above *should* work. There are some bugs though. More importantly there are some big missing features.

**Fetching**: The biggest missing feature in this release is an improved fetching and filtering system. You may notice all of your pull requests dont show up. Especially if they are old or there hasn't been much recent activity on them. 

**Filtering**: Those three little boxes above the list don't do anything right now. In the future they will be part of the filtering and triage system. You'll be able to put your pull requests into three different boxes: starred, inbox, and archive. The filtering system lets you easily triage pull requests and build rules for automatically putting new stuff in the correct box. Sounds awesome doesn't it? Too bad it doesn't work yet.

**Search**: Search doesn't work either and will be added when the new fetching and filtering system is complete.

**FullScreen**: Lets just say full screen mode is experimental. It only works in Landscape mode and if you enter it in landscape, then switch to portrait you wont be able to leave. There also aren't controls for toggling through pull requests or between activity & changes. Also you'll notice that items aren't properly sized in full screen. So you might get a bunch of whitespace under comments.

**Individual Commit View**: Its ugly. I'm sorry. I will do better next time.

**Tapping User Names**: Tapping user names will open a dialog giving you info on a user. "Who is this guy that wants to change my SSL code? Oh he works for the NSA, guess I'll accept this." 

**Tapping / long pressing**: Everything that is light blue should be tappable. Commits, usernames, repos, file names, ect. Anything that isn't tappable right now will be. But they should also be long pressable. A long press would allow you to access a URL to an item on the GitHub site. So you can long press, Open in Safari, Send Link, ect.

**Merging**: This is disabled in the current beta. It will be back soon though.

**Saving Draft Comments**: Currently if a comment fails to post it is lost forever. Future versions will allow you to access draft comments and will automatically upload comments that failed due to network activity.

