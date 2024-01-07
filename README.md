# Data-Scrapping-And-Visualizations
Data Scrapping 3rd Semester Project 
# Data-Scrapping-and-Visualization

National University of Computer and Emerging Sciences Chiniot-Faisalabad Campus 

BS (Artificial Intelligence)

Contribution 
1: Najeeb Ullah
2: Hamna alim 
3: Hamyal
Course	Programming For Ai 
Project	Web Scrapping (Messari API)
Department	Computer Science

  
CryptoData Class
This class manages cryptocurrency data, allowing cleaning, transformation, statistical analysis, and visualization.

Methods:
__init__(self, df)

Initializes a CryptoData object with a DataFrame.

clean_data(self)

Cleans the DataFrame by handling missing values and converting date columns to datetime objects.

transform_to_log_returns(self)

Converts price data into log returns and handles missing values.

add_statistics_to_csv(self, filename)

Generates statistics on the DataFrame and appends them to a CSV file.

identify_date_highest_return(self)

Identifies dates with the highest return for each cryptocurrency.

get_highest_opening_price(self)

Retrieves the highest opening price from the dataset.

plot_historical_prices(self, crypto_name)

Plots historical prices for a given cryptocurrency.

plot_mean_returns_comparison(self, crypto_name)

Compares mean returns among cryptocurrencies through visualization.

plot_correlation_matrix(self)

Displays a correlation matrix plot for cryptocurrencies.

plot_3d_prices(self, crypto_name)

Visualizes 3D price plots for cryptocurrencies.

Functions:

scrape_crypto_prices(crypto_symbol)

Fetches cryptocurrency data from an API based on the provided symbol.

display_menu_gui()

Displays a GUI menu for user interaction.

print_colored(text, color)

Prints text in the specified color in the console.

scrape_manage_calculate(crypto)

Orchestrates data scraping, management, and calculations for a specific cryptocurrency.

main()

The main function handling user interactions, data fetching, analysis, and visualization based on user choices.

Usage Instructions:

Data Fetching and Analysis Options

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/0fe55bdc-778a-4956-b4e4-8282f7e2a96d)

Option 1: Scrap CoinCap for specific cryptocurrencies.

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/6e2cc0dc-b692-4c1d-8d53-80d6788ae126)

Option 2: Display correlation matrices.

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/6dd16ec1-a04c-4ce7-819b-385ce68c969b)

Option 3: Visualize historical prices and 3D plots.

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/62280568-7746-4c97-9ed9-c8165a82a2dc)

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/fbc4978f-2865-4be7-a1cf-c48006ccb43e)

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/887a80cb-24d2-46ea-bf22-185bab08dc10)

Option 4: Calculate statistics for a specific cryptocurrency.

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/e224e525-fbed-4640-89ad-06543eaf5ff8)

Option 5: Visualize mean return comparisons among cryptocurrencies.

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/2d10333d-932b-45c3-aafc-d4e652de77a5)

![image](https://github.com/Najeebullah3124/Data-Scrapping-and-Visualization/assets/147226547/48da5195-09b6-4cc9-baf6-36b0703fafb5)


Execution

The program starts by displaying a menu GUI to select desired actions.

It continuously runs until the user chooses to exit.

User Input

Users can select options to perform specific tasks related to cryptocurrency data analysis, visualization, and calculations

