# AdvancedWare-Assignment

### Random User Data Generator and Sorter
This project contains Python code to generate random user data, save it to a CSV file, and sort the data based on a specified field.

### Getting Started
These instructions will help you get a copy of the project up and running on your local machine.

### Prerequisites
You need to have the following packages installed on your machine:

requests
pandas
You can install these packages using the following command:

<code> pip install requests pandas </code>

### Generating User Data
The generate_random_user_data function uses the Random User Data API (https://random-data-api.com/documentation) to get random user data. The function takes two arguments:

num_users: The number of users to generate data for.
interval: The interval time in seconds between each request to the API.
The generated user data is saved to a CSV file named "users.csv".

### Sorting User Data
The sort_csv function sorts the user data in the "users.csv" file based on a specified field. The function takes two arguments:

file_path: The path to the CSV file to sort.
sort_field: The field to sort the data on.
The sorted user data is saved to a new CSV file named "users-sorted.csv".

### Displaying User Data
The get_user_details function takes an username as input and returns the details of the user from the "users.csv" file.

### Running the Examples
You can run the examples in the AdvancedWare.ipynb notebook file to see the functions in action.

### Conclusion
This project demonstrates the use of the requests and pandas packages to generate, sort, and retrieve user data from a CSV file. By using this project, you can easily generate and sort large amounts of random user data for testing and demonstration purposes.
