# pymail
Command line email sending!

Pymail sends emails through the command line, with python's built-in smtp libs.

The config file goes in ~/.pymail/config.ini, and a default config file is included, make sure that you edit it to have your information.

The command line arguments are as follows:

pymail <Recipient> <Subject> <Body> <attachment> (Any other arguments are treated as paths to an attachment.)

If the arguments are not passed, the program will revert to the defaults defined in the config file, except for the attachments, which will remain empty.

I made this program for bash scripting, and it works well enough for me, but let me know if you wish it had another feature, or something is broken. 
