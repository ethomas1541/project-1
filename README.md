Elijah Thomas
ethomas7@uoregon.edu

CS 322 Project 1

Simple web server implementation demonstrating use cases for common HTTP errors like 403 and 404

403 is transmitted when a request contains illegal or otherwise unworkable characters or orders of those characters

404 is transmitted when a request is syntactically valid but refers to a file which does not exist
    It may also transmit if the file referred to is a directory (DOCROOT itself or a subdirectory within)