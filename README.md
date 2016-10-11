# hello-world
Test repository to see if I can create a repository, branches, and commit changes.
Let's see if I can commit changes.

*How will this text appear*
_and how about this_
**and what about this?**
```psql -f type```


1. VirtualBox: https://www.virtualbox.org/wiki/Downloads
2. Vagrant: https://www.vagrantup.com/downloads.html
3. GitHub repository from Udacity: https://github.com/udacity/fullstack-nanodegree-vm

[VirtualBox] (https://www.virtualbox.org/wiki/Downloads)

1. [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. [Vagrant](https://www.vagrantup.com/downloads.html)
3. [GitHub repository from Udacity](https://github.com/udacity/fullstack-nanodegree-vm)

*tournament.sql*

wiss-Style Tournament Database

What is it?
-----------

This module creates a database to store names, track records, and match players in a
Swiss-system tournament. The module contains three files: tournament.sql, tournament.py,
tournament_test.py


Description of files
--------------------

*tournament.sql*
	This file contains the database schema for a tournament database: all
	of the psql commands to create one database (tournament) with two tables and three views.

*tournament.py*
	This file contains the functions to register, report, rank, and pair participants
	in the tournament.

*tournament_test.py*
	This file contains test cases to evaluate the functions in tournament.py. All of
	the code in this file is courtesy of Udacity. The only change I made was to add
	function calls.


Additional required software and code
-------------------------------------

1. [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. [Vagrant](https://www.vagrantup.com/downloads.html)
3. [GitHub repository from Udacity](https://github.com/udacity/fullstack-nanodegree-vm)


Database setup and testing
--------------------------

From within the VM, `cd` into `/vagrant/tournament` from the fullstack repository. To
import the database, do the following: from the tournament directory,
type `psql -f tournament.sql` (or if in psql, type `\i tournament.sql`).
**Note:**importing the database will delete any previously existing database named
'tournament'.

Test database: from the tournament directory, type `python tournament_test.py`.


Versions
-------------

This module was built and run on the following:
macOS 10.10.5
Python 2.7.12
VirtualBox 5.1.6
Vagrant 1.8.6
