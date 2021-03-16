## Big_Data_Project

# Tools used - 
Pyspark, SQL

# Process - 
# Data Preprocessing - 
The dataset contains the detailed information of football players of FIFA 2019. 
Preprocessing contains following steps.
- Removal of unnecessary columns in the dataset, symbols.
- Converting value attributes to floating values
- Feature scaling using nib-max normalization
- Delete the rows which contains null values

# Data Analysis and Data visualization -
- Finding correlation between Overall player ratings, Age and Potential of players with market value of each player.
- Finding the two columns which have maximum correlation.
- The maximum correlation observed is for Overall player ratings and market value of each player.
- Plotting Overall player ratings and market value of each player along with required plot properties
- Visualizing relation between age with market value and overall player rating
- Plotting how market value of players vary with age with required plot properties
- Plotting how overall player rating varies with age with required plot properties
- Finding top 10 best players with respect to each position considering their overall
- Plotting average market value of top 10 worthy players for each position with required plot properties
- Plotting average overall of top 10 worthy players for each position with required plot properties
- Plotting average overall of 10 least worthy players for each position with required plot properties
- Using k-means clustering between overall player ratings and market value as these two attributes have the highest correlation for the best players
