# Python Entry Test for Microdata
Perform the following tasks:
- Clone this repository to your computer
- Write a python code that performs the following (try to write a nice and clean code as you would in MicroData):
  - Read in `ids.pickle`. It contains mock ids in a list, and they each should be 14 digits long, but someone mistakenly stored them as integers instead of strings. The problem is that these ids may start with zeros, and those are cut off if stored as integers. Transform them in a way to retrieve the correct IDs.
  - Once you have the correct IDs cut out the 3rd and 4th digit from each ID. These form a made-up county code. You can find a translation table in `id-to-county.csv`. This also suffers from the above mentioned issue, `Sorszám` is stored as an integer.
  - Your task is to count how many IDs belong to each county. You can perform this task any way you prefer as long as your solution is correct.
  - Save your results in `id-count-by-county.csv` in the data folder. It should contain two columns: The name of the county (only the county, not the registry court) and the number of IDs belonging to that county.
- Commit your code and your results.
- Push these back to your repository.

