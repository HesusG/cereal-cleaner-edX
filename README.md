# Instructions

* Open the file, `cereal.csv` and start by skipping the header row. See hints below for this.

* Read through the remaining rows and find the cereals that contain five grams of fiber or more, printing the data from those rows to the terminal.

## Hint

* Everything within the csv is stored as a string and certain rows have a decimal. This means that they will have to be cast to be used.

* The csv.Reader begins reading the csv file at the first row. `next(csv_reader, None)` will skip the header row. Refer to this stackoverflow answer on [how to skip the header](https://stackoverflow.com/a/14257599) for more information.

* Integers in Python are whole numbers and, as such, cannot contain decimals. As such, your numbers containing decimal points will have to be cast as a `float.

## Bonus

* Try the following again but this time using `cereal_bonus.csv`, which does not include a header.

# Additional Material

You can find more information on today's lesson. 

- [Python Data Types](https://www.geeksforgeeks.org/python-data-types/)
 

- [Difference betwen int and float](https://www.delftstack.com/howto/python/float-vs-int-in-python/)

- [CSV Files History](https://blog.sqlizer.io/posts/csv-history/)


## FAQ: 

Please find a set of frequently asked questions for the cereal cleaner activity in the following document:

- [Class # - FAQ](https://docs.google.com/document/d/1MVl6ae33JBvjPIGN677Kqh4W7cvHDGAwNGJmG4AjnLI/edit?usp=sharing)
