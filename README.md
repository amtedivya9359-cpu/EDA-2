# EDA-2
🧠 Breakdown of Components:

• pd: Refers to the pandas library, commonly used for data manipulation and analysis.

• read_csv(): A pandas function that reads a Comma-Separated Values (CSV) file and converts it into a structured DataFrame.

• "movies_updated.csv": The filename of the dataset you're importing. It should be located in your current working directory or you need to provide the full path.

• df: The variable that stores the resulting DataFrame, which now contains all the data from the CSV file.

📊 What Happens After This Line:

• Once executed, df will contain a structured table with rows and columns representing movie data. Based on your previous screenshots, this dataset includes:

🧾 Columns Likely Present:

• name: Movie title

• rating: Age classification (e.g., PG, R)

• genre: Primary genre

• year: Release year

• released: Full release date

• score: Viewer or critic rating

• votes: Number of audience votes

• director, writer, star: Key creative personnel

• country: Country of origin

• budget: Production budget

• gross: Box office earnings

• company: Production/distribution company

• runtime: Duration in minutes

🧹 Optional Enhancements After Loading:

•  You might want to clean or inspect the data right after loading:

• python
  •  df.info()         # Overview of column types and non-null counts
  •  df.describe()     # Summary statistics for numeric columns
  •  df.head()         # Preview the first few rows
  •  df.isnull().sum() # Check for missing values
🔍 Why This Matters:

• Loading the dataset is the first step in any data analysis workflow. It allows you to:

• Explore trends (e.g., budget vs gross)

• Visualize distributions (e.g., scores, votes)

• Identify top performers (e.g., highest-rated or most-voted movies)

•  Build predictive models (e.g., estimating gross based on budget and genre)
