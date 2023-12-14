# PSSaDMS
Python Secure Storage and Document Management System
Still working on the framework, I'll be back to you all as soon as I've got more progress! Right now, I have the basics for a document manager, which can use SHA 1-512(+salt!) to encrypt your documents that you need to keep safe
I'm also still implementing the basic $upload functionality, for now, it will have to use a Google Developer Google Drive API Key, until I can figure out how to allow users to log into their Google account
I also have to add in the $drv command, which should pull up a Google login page, which once the user logs in, it will connect itself to their drive, which they can then do $quit to kill the process entirely, or $trf(or $download, haven't picked yet) [filename] [directoryoutput]
