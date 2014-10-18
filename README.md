SQLite play
===========

Just some code that I was using to experiment with SQLite

### Usage directions

download the [SQLite src](http://www.sqlite.org/download.html), place in directory (same directory as test.c). Extract the contents to its own child directory, for this example it should be named sqlite. It's necessary to use gcc to compile sqlite as g++ will cause a whole lotta errors.

create the test.c file.

From the command line:

```gcc test.c -I sqlite sqlite/sqlite3.c -lpthread -ldl```