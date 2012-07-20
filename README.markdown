## Developer Newsletter

Accessible at [http://unboxed.github.com/newsletter/](http://unboxed.github.com/newsletter/)

## Uh oh, it's my turn, what do I do?

Send out an email asking for contributions from everyone.

* Clone this repository
* Run ```bundle install```
* Run ```rake new_post```
* Commit / push post
* If it's your first time:
    * Run ```rake setup_github_pages```:
        * You will be prompted for the git repo, enter the following: ```git@github.com:unboxed/newsletter.git```
* If it's you've done it before:
    * you could try:
        * ```cd _deploy; git pull``` to update the _deploy branch, but this might give you merge conflicts.
    * so if it does, or you're too lazy to try:
        * ```rm -rf _deploy; rake setup_github_pages``` and fill in the repo again to get a fresh copy
* Run ```rake gen_deploy```

Then email everyone saying the new newsletter is out.  Then go into the dev chatroom and ask bender to choose someone new for the newsletter by saying the following:

* seed the newsletter
* newsletter

The first asks bender to make sure the list of people who can do it is complete, the second asks bender to choose someone from that list.  Check the holidays on the wiki, and if the chosen person is available it's your job to let them know.  If they're in the room that's great, but emailing them can't hurt.  If the chosen person isn't available, just ask bender to choose someone else with ```newsletter``` (no need to seed this time as you don't want to keep picking the unavailable person).