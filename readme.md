# readme.md

## writing new posts

Prepare the post via

`$ hexo new draft <title>`

eg

`$ hexo new draft test`

(You don't need the .md)

Then open it in text editor, fill in all the required information etc. The piece will now be in the `_drafts` folder. These do not get generated.

To put it online though for the individual to check it out, we can do it all sneaky like:

`$ hexo generate --draft`

Take note of the path for the rendered piece.

Then deploy it to the github version.

`$ hexo deploy`.

**nb** don't deploy to github. use ftp to move it to the library server. see below

Check that it's actually there, share that with the author, make sure they understand not to share it any further.

## publishing the posts

Once the author agrees that all is good, use `publish` to move it to the `_posts` folder:

`$ hexo publish draft test`

Then generate the site:

`$ hexo clean` <- don't do this unless you really have to (ie, cleaning out things that were never meant to be published). It seems to re-write all the timestamps on the files or something, thus ftp loads *everything* instead of just the new stuff.

`$ hexo generate`

*we will not be deploying the finished site to the github version anymore*

Connect to the vpn no matter what in order to connect to the official server

FTP the contents of the public folder over. Select 'overwrite if different size' for the queue.

PROBLEM I wonder if not deploying contents to github will cause trouble, people thinking that that's the real site. Maybe don't deploy drafts to github. Do it all ftp, and just leave a note on the former site redirecting people to the real site. That's probably best. Too bad, deploy was such a handy command.
