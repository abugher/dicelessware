If you don't trust your computer to produce random bits securely, use
diceware to generate passwords, which involves physical dice and a
printed word list.  If you do trust your computer (or you think cameras
can see your dice and word list), you can use dicelessware.

You'll need a dictionary file at this location:

  $HOME/.dicelessware/active_list.txt


Usage:

  dw <wordcount>

    Generate a pass phrase with wordcount words.

  viwl [-f <file>]

    Edit the default custom word list, or the specified file.

  pin <charcount>

    Generate a PIN with charcount digits.
