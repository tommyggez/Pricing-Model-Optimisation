# A general pricing optimiser based on probability theory and net utility economic model

This model operates under the assumption that individuals have a internal value V of the good you are selling, and will buy it if the net utility = V-p is positive.
We assume internal value is normally distributed in the population, and we know the mean and standard deviation.
We can calculate the optimal price to be the price p that maximises (p-c)*E(sales), where c is the variable cost of production of one item and E(sales) is the expected number of sales.
The equation can be optimised by optimising (p-c)*P(sale).

The closed form is not solved, however it is possible to numerically optimise this for a variety of different populations and variable costs, which is shown in the notebook.
