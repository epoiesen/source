# readme.md

## writing new posts

Prepare the post via

`$ hexo new draft <title>`

eg

`$ hexo new draft test`

(You don't need the .md)

Then open it in text editor, fill in all the required information etc. The piece will now be in the `_drafts` folder. These do not get generated.

**Note** in the yaml header, the author key **has** to be between " quotes, not ' quotes. Otherwise the author index doesn't work correctly

To put it online though for the individual to check it out, we can do it all sneaky like:

`$ hexo generate --draft`

Take note of the path for the rendered piece.

**Feb 2018** update:

- updated hexo and dependencies because of security issues. this seems to have broken the draft generation. On the local server, it stills behaves as expected: the new piece is not in the index or displayed on the front page, but can be accessed via the direct URL. HOWEVER, when pushing to the live server, the draft appears on the index.

So: write in the draft folder, generate draft, then check the generated index.html in the public folder. Remove the div containing the draft if it is there.

If there is a piece that is taking some time to develop, put it in the `_private_drafts` folder and work on it there. This is not optimal, but until I figure out a fix...

OUTDATED:
```
Then deploy it to the github version.

$ hexo deploy
```

**nb** don't deploy to github. use ftp to move it to the library server. see below

Check that it's actually there, share that with the author, make sure they understand not to share it any further.

## publishing the posts

Once the author agrees that all is good, use `publish` to move it to the `_posts` folder:

`$ hexo publish draft test`

**double check** that no extraneous things have been inserted into the md file. This is because I interfered with the scaffolds file 'post.md'. All should be fine now, but make sure. Pay particular attention to the yaml header and the other metadata.

Then generate the site:

`$ hexo clean` <- don't do this unless you really have to (ie, cleaning out things that were never meant to be published). It seems to re-write all the timestamps on the files or something, thus ftp loads *everything* instead of just the new stuff.

`$ hexo generate`

*we will not be deploying the finished site to the github version anymore*

Connect to the vpn no matter what in order to connect to the official server

FTP the contents of the public folder over. Select 'overwrite if different size' for the queue.
