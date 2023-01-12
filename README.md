# FoodStylesChallenge


## The challenge (Solved The challenge only, While the bonus is Excluded)

You are given a dataset (assets/dataset.zip) containing information about restaurants all over Europe. The goal of the challenge is to make sense of the dataset and understand it in such a way that informed, data-based business decisions can be made. To make things easier, the challenge is split into three conceptually independent parts, with action points at each part.

### Data cleaning
- Identify the columns with mixed data types.
- For each column, count the number of rows per data type.
- Would removing missing values solve the mixed data type problem?

### Data understanding
- Are the review columns correlated with the rating columns? 
- Review columns: ["excellent", "very_good", "average", "poor", "terrible", "total_reviews_count", "reviews_count_in_default_language"]
- Rating columns: ["food", "service", "value", "atmosphere", "avg_rating"]
- Are vegetarian-friendly restaurants better than non-vegetarian ones?
- Are there any significantly more expensive cuisines?

### Business-specific
- In the assets directory, you will see a very small dataset called europe_capitals_population_and_area.csv. A gluten-free restaurant wants to open a new restaurant in a European capital where gluten-free restaurants are underrepresented. Assuming there are no other factors, except population and gluten-free restaurant density, what would be the top 5 capitals to open that restaurant?
- Think and propose a couple of other ways this dataset could be used to help businesses.

## Getting Started

- Download the dataset from the assets folder
- Run the code to perform data cleaning, data understanding and business-specific analysis
- Use the insights to make informed decisions
