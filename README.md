# b64
I got tired of using online base64 tools, so I decided to write my own command line tool to get the job done quicker.

# Prerequisites
* You have the latest version of Python3 installed.
* You are using a linux machine. Windows and MacOS is not currently supported.
* You understand the basics of what base64 is

# Installation
Firstly, you need the script. You can do this one of two ways:

1) Clone the repository:

<pre>git clone https://github.com/nochhacks/b64.git</pre>

2) Diriectly download the ZIP file from the "Code" section above the landing page.


Next up, make sure that the script is executable:
<pre>chmod +x b64</pre>

After this, if you want to use the command from anywhere in the terminal, you will need to add this entry to the bottom of your .bashrc file with the following:
<pre>export PATH=/home/path-to-b64-script:$PATH</pre>

The .bashrc file is executed each time a terminal window is opened, so it will add the desired script filepath to the $PATH variable.

# HELP PAGE:

<pre>USAGE: b64 [option] <string>
  
  Options:
  
      --decode-string (-d) <base64 encoded string>
      --encode-string (-e) <String to be encoded in base64> | Use quotes ""
      --help          (-h)

  Example: b64 --encode-string "Hello World!"

</pre>
