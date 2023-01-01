# Feedback for Problem 2

* The standard csv way to read a file is to use the reader class in the csv module, but if you observe the data, it's almost like a text file, just that it's structured column-wise as well.
* So a nice way to read this (especially since it has no header, which csv files usually have) is to treat it like a text file and read it line by line into a list, and then split the string with the ',' character, and you get what you want.
* If you want feedback for the other parts, do try them out on your own way first, I'd like to see some effort before I reveal what is to be done (it isn't that hard though so you should be able to do it)
