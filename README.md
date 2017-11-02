# TestLFS
This is just to see how LFS support works.

Sorted ssh authentication :-)

Sorted gpg signing ;-)

Some progress!

OK So this is how it works:
Choose the (potentially) big files (or file types) and 
add them to the .gitattributes file.
Add .gitattribites to your repo!
git lfs {track,ls-files,env} are useful info commands.
If you (accidentally!) transfer a file to the lfs server you can recover it
by:
git checkout -- <filename>
