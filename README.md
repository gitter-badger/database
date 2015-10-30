OneDatabase
==========

[![Join the chat at https://gitter.im/kotishe/database](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/kotishe/database?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

License
-------
**OneDatabase** is released under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0.
The file (`LICENSE.md`) **must** be a part of any redistributable packages
made from this software.  No licenses should be removed from this software if
you are making redistributable copies.

How to Install
-------
Short instruction:

1. enter _tools directory

2. run: make_full_db.bat (if you are doing it under Windows) or run: /bin/sh make_full_db.sh (if you are running
   it under *nix/Linux)

3. apply created file to mangos database, eg.: mysql -u root -p mangos < full_db.sql

That's all!
