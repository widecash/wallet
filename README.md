Widecash Wallet
===========================

Where is my blockchain data directory?

Operating System             

Windows 7, 8.1, 10

Default Directory: %APPDATA%\widecash\	   
Full Configuration File Path: C:\Users\username\AppData\Roaming\widecash\widecash.conf

Linux

Default Directory: $HOME/.widecash/	            
Full Configuration File Path: /home/username/.widecash/widecash.conf

How can I backup wallet ?

1) Close your wallet. 
2) Open the folder "%APPDATA%\widecash\". 
3) Copy the file wallet.dat to a safe location.

How can I restore wallet?

1) Close your wallet. 
2) Make a backup of the folder "%APPDATA%\widecash\". 
3) Copy the file wallet.dat from your backup to the folder "%APPDATA%\widecash\".

What is Widecash?
===========================
Widecash is an experimental digital currency that enables instant payments to anyone, anywhere in the world. Widecash uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Widecash Core is the name of open source software which enables the use of this currency.

License
===========================
Widecash Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of WideCash.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
