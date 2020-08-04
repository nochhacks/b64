# base64
A simple command line tool built to decode and encode base64 strings.

This tool was written in python, however to execute it from a linux terminal you must give the file the necessary permissions:
<pre>chmod +x base64</pre>

After this, you will need to edit your .bashrc file with the following:
<pre>export PATH=/home/path-to-base64-script:$PATH</pre>

This file is executed each time a terminal window is opened, so it will add the desired script filepath to the $PATH variable.

HELP PAGE:

<pre>USAGE: base64 [option] <string>
  
  Options:
  
      --decode-string (-d) <base64 encoded string>
      --encode-string (-e) <String to be encoded in base64> | Use quotes ""
      --help          (-h)
</pre>
