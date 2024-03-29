This project is an assignment for my Python class. For the assignment I will do the following:

* Create a README file
* Download a [data file](https://github.com/CorkCork/Analytics-Programming/blob/master/Module%204/Data/Water_Consumption_In_The_New_York_City.csv) from NYC's Open Data Portal. You can find out more about this data at https://data.cityofnewyork.us/Environment/Water-Consumption-In-The-New-York-City/ia2d-e54m.
* Create a [Jupyter Notebook](https://github.com/CorkCork/Analytics-Programming/blob/master/Module%204/Module%204.ipynb)

In the [Jupyter Notebook](https://github.com/CorkCork/Analytics-Programming/blob/master/Module%204/Module%204.ipynb), I'm going to do the following:

* Use the numpy module 'genfromtxt' to import a .csv file that has NYC water use and make it into a numpy array.
* Check the type of the numpy array, and display it, without scientific notation.
* Answer the following questions, using numpy slicing and operations:
      - What is the maximum yearly NYC consumption in millions of gallons per day?
      - How many years are represented in this data?
      - What is the mean and the standard deviation of the per capita daily water consumption?
      - What is the increase or decrease in population from year to year? Use numpy's diff function to create an array of differences and save that to the variable pop_diff, then print that variable.
      - What's the python type (use type) of pop_diff?
      - What's the numpy datatype (use numpy's dtype) of pop_diff?
      - How many elements are in pop_diff? Why is that different from the number of rows in our 2D array?
* Create a simulation of per capita daily water use over this time frame.
* Then, using numpy's random package, create an array that contains that number of values, normally distributed, with the mean and standard deviation you figured out for per capita daily water use, saving that array to simulated_daily_use_array.
* Check that simulated_daily_use_array is actually a numpy array, and create a list that has the exact same values, but isn't an array, but rather a list called simulated_daily_use_list.

After all of that (🎯), I will do some profiling of performance with code provided to me. I will use three different methods to find the square root of each simulated water use, and I'll use 'timeit' to figure out what is quickest.