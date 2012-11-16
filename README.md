Synopsis
--------

A bash script that, given a PID, will email specified recipients when the process finishes.


Usage
-----

$ whenitsdone 1234

$ whenitsdone 9876 jon@jonbevan.me.uk

$ whenitsdone 1337 jon@jonbevan.me.uk "All files have been deleted"


If no email addresses are supplied, no alerts will be sent unless a file ~/.whenitsdone exists, in which case an email address will be read 
from each line and alerts CC'd to those addresses.
