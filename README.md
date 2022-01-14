# dspAdmin
.NET-based DSP server administration program


This is a project I started a few years back to be able to administer a local DSP install such as editing characters, monsters, etc.

You will notice that the initial commit has a lot of bad coding in it.

Feel free to pull and use, if you make improvements please push them back so everyone can benefit.


Thanks!
- Whasf

v0.5.3
A few things repaired, updated the title form to FFXI Administrator since DSP no longer exists which is sad. (leaving the namespace to dspadmin)

SQL connector updated to work properly with .NET 4.5.2 

Removed a bunch of redundant code.

disabled the dispose of the connections(2,3) so that inventory list wouldn't crash out, should move the list up the code so this doesn't need a fix.

Removed depreciated Tables and updated item_armor to item_equipment

