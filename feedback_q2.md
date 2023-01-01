# Feedback for Problem 2

## Loading Data 

* The standard csv way to read a file is to use the reader class in the csv module, but if you observe the data, it's almost like a text file, just that it's structured column-wise as well.
* So a nice way to read this (especially since it has no header, which csv files usually have) is to treat it like a text file and read it line by line into a list, and then split the string with the ',' character, and you get what you want.
* Since you haven't used both of them, I'd suggest that you also try out reading from a csv file and from a text file, even though you'll have libraries like `Pandas` to help you out with this in the future, you'll need to know how to load assignments from these in the future.

## Organising Data

* Instead of using delete, you could have sliced the matrix as well, to give you everything except the first column. Slicing is really powerful, for arrays in `NumPy`.

## Grouping the Data

* I think I already discussed this with you, so I'm not giving any feedback on this :)
* But do check these two links out as well, they talk about group by using pure NumPy : https://stackoverflow.com/questions/49372918/group-numpy-into-multiple-sub-arrays-using-an-array-of-values and https://stackoverflow.com/questions/49141969/vectorized-groupby-with-numpy?noredirect=1&lq=1

Once you've grouped the data, finding mean images is pretty easy, so even though you've not done it, I guess you can do it

Nice job :)
