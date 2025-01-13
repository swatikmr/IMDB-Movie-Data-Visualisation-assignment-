
### IMDb Movie Assignment 

# IMDb Movie Analysis Project

## Overview
This project analyzes data from IMDb's top 100 rated movies from the past decade. The analysis includes profit calculations, audience demographics, genre analysis, and geographical viewing patterns using Python and its data science libraries.

## Prerequisites
- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - IPython (for Jupyter notebook functionality)

## Dataset
The dataset (`Movie+Assignment+Data.csv`) contains information about:
- Movie metadata (title, budget, gross earnings, runtime)
- Ratings (IMDb rating, Metacritic score)
- Actor information (names, Facebook likes)
- Audience demographics (votes by age group, gender, and location)
- Movie characteristics (genre, content rating, country)

## Project Structure
The analysis is divided into three main tasks:

### Task 1: Data Loading and Inspection
- Reading the movie dataset
- Checking dimensions, null values, and summary statistics
- Initial data exploration

### Task 2: Data Analysis
1. **Financial Analysis**
   - Converting budget and gross to millions
   - Calculating and analyzing movie profits
   - Creating profit vs. budget visualizations

2. **Rating Analysis**
   - Comparing critic (Metacritic) and audience (IMDb) ratings
   - Identifying universally acclaimed movies
   - Analyzing rating patterns

3. **Actor Popularity Analysis**
   - Finding popular actor trios based on Facebook likes
   - Implementing sophisticated filtering for balanced actor groups

4. **Movie Characteristics Analysis**
   - Runtime distribution analysis
   - R-rated movies popularity among different age groups

### Task 3: Demographic Analysis
1. **Genre Analysis**
   - Combining and aggregating genre data
   - Creating genre distribution visualizations
   - Analyzing genre popularity

2. **Gender and Age Analysis**
   - Creating heatmaps for voting patterns by gender and age
   - Analyzing genre preferences across demographics

3. **Geographical Analysis**
   - Comparing US vs non-US audience preferences
   - Analyzing voting patterns based on movie origin

## Key Visualizations
- Profit vs Budget scatter plot
- Runtime distribution plot
- Genre count bar charts
- Gender and age group heatmaps
- US vs non-US box plots
- Top 1000 voters' genre preferences

## Key Findings
1. Many movies with budgets under $50 million cluster around zero profit
2. Some movies show negative profit due to domestic-only gross figures
3. Drama is the most common genre in the dataset
4. Sci-Fi is most popular among the 18-29 age group across genders
5. Non-US audiences tend to vote more frequently regardless of movie origin
6. Romance appears least popular among top 1000 voters

## Usage
The code is structured as a Jupyter notebook and can be run sequentially. Make sure to:
1. Install all required dependencies
2. Update the dataset path in the code
3. Run the cells in order to maintain data consistency

## Data Processing Notes
- Budget and gross values are converted to millions for better readability
- Metacritic scores are scaled down by factor of 10 for comparison with IMDb ratings
- Genre analysis combines primary, secondary, and tertiary genre classifications

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is available under the MIT License. See the LICENSE file for more details.

