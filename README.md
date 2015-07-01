define-a-list-of-words
======================

This is a collection of bash scripts that takes a list of words (that you have in a file named "words"), defines them, and writes that definition to a file known as defsout.txt.

It's a great tool for collecting a lot of definitions into a file at once. 

The code isn't terribly pretty, and if a certain word isn't in the dictionary, then it will write an error message instead of a definition, but as long as your dictionary is large, up-to-date, and you aren't using any crazy words, then this script will do the job (and do it well).

Before use, be sure to install the sdcv package, and follow this tutorial to load a dictionary onto your machine:
http://linuxtidbits.wordpress.com/2008/01/30/command-line-dictionary/

Since the link to the StarLink tarball in that tutorial is dead, use this link instead:
http://abloz.com/huzheng/stardict-dic/dict.org/

Since the file getdefs.sh is the script from that site, you won't need to do anything else except install sdcv and load the dictionary (a ~10M tarball) onto your machine. 

then, you may proceed.

I have a list of words loaded into the words file as an example, but you can replace these with the words you want to define. 

Have fun!
