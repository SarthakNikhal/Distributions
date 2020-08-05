# Distributions

This is a package used for distribution of data and plotting it.

## Installation

Run the following to install:

'''python
pip install nixz_probability
'''

Usage

'''python
from nixz_probability import Binomialdistributions
(or)
from nixz_probability import Gaussiandistributions

# Feed Data
Use read_data_file(file_name) method to feed data
You can directly use the distribution classes after feeding data to the program.

#Use methods to calculate and plot
#calculate mean of data
object.calculate_mean() calculates mean of the data

#calculate standard deviation
object.calculate_stdev(False->if data is population)

#plot histogram of data
object.plot_histogram

#generate probability density for given example
object.pdf(test_example)

#plot histogram for proability density function along same range
object.plot_histogram_pdf(number_of_spaces)

#add 2 Binomial or Gaussian distributions
distribution1 + distribution2

#represent a distribution
distribution1