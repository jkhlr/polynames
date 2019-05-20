# polynames
Analyzing the gender distribution of the names given by users to the polyhedra at [Polytopia](https://www.polytopia.eu/en/)

### Dataset

- A list of nicknames given to the "adopted" polyhedrda at [Polytopia](https://www.polytopia.eu/en/)
- A dataset of first names with their associated gender from [here](https://github.com/MatthiasWinkelmann/firstname-database/blob/master/firstnames.csv)

### Method

For each nickname, we find all first names that are part of the nickname. Using the connection of first names to a gender from the first name dataset, we assign a gender probability to each nickname.

### Results

The gender distribution of names is pretty balanced. However, only roughly half of the nicknames could clearly be associated with a gender.

### Interpretation

Possible explainations for the observed results:

- The geometry and appearance of a polyhedron does not obviously imply a gender
- Nicknames such as `Larissas Polyeder` suggest that users give their own name to their adopted polyhedra. In this case, this analysis would imply that the user-base of Polytopia has a gender-balanced user base 
