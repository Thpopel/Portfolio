# Hello and Welcome!
My name is Thomas, and I'm a Bachelor of Science student completing a major in Neuroscience with a minor in Computer Science at Dalhousie University in Halifax, Nova Scotia. This portfolio is an opportunity for me to showcase some of the coding skills I have been developing over the past semester. Enjoy! 

**Together, we will take a look at the following:**
- Slicing 1D and 2D Lists/Arrays
- For Loops 
- Descriptive Statistics and Manipulation of Dataframes
- Exploratory Data Analysis
- EEG Data Visualization 

### Slicing 1D and 2D Lists/Arrays:
To begin this portfolio I'd like to start by showing a demonstration on slicing values from a 1D or 2D list, and/or arrays. Please click [here](Slicingvalues.md) to view this topic in greater detail. 

### Descriptive Statistics and Manipulation of Dataframes:
**Descriptive statistic** are another vital component of data analysis. By utilizing different tools provided by different modules, we can maximize efficiency and accuracy. 

Please click [here](descriptivestats.md) to view this topic in greater detail.

Some methods I'll be using in my example of manipulating a dataframe include:
- `head`: Provides the option to view the first n items in our dataframe.
- `type`: Provides the type of data we are working with
- `describe`: Provides an overall view of the descriptive statistics 
- `unique`: Provides a list of unique values within that column

To understand the use of these methods, we'll first import a dataframe. The dataframe is a list of the highest selling video games.
- **Importing a data file:** [Importing data](Import_data.md)

Next, we'll take a look at some of the descriptive statistics using describe()
- **Describe():** [Describing data](Describe.md)

Now that we have a datafile imported and we know what it looks like, let's filter out the Platform column we're interested in, and see the unique values. As we can see, there are quite a few unique values. Therefore, we are going to take a look at the newer platforms in the data (XBOX360, Wii, PS3):
- **Selecting the columns and rows we're interested in:** [Selcting data](Sorting.md)

Lastly, let's calculate the total sales each platform has made with their collection of games in global sales, and calculate that as a percentage of a whole for all three platforms:
- **Calculating total sales, and sorting percentages:** [Calculating data](DataCalculations.md)

As we can see from our calculations of total sales, the three platforms are fairly close in global sales. It's important to note however, that the xbox360 was released a year earlier than the other platforms we are discussing. 

### Exploratory Data Analysis:
I learned very early on of the benefits of **Exploratory Data Analysis (EDA)** in communicating results. Carrying on with our video game data calculations, lets visualize the results.
- **Data visualization:** [Data visualization](Datapic.ipynb)

**Jargon Listed in this Portfolio:**
- **Logical errors:** Logical errors are errors that do not cause the program to terminate abnormally, but instead are mistakes in a program's code that cause it to produce an unexpected or incorrect response or calculation. 
- **Pandas ILOC method:** The LOC method returns rows from a dataframe given an inputted integer slice. 

_Questions? Please email me at_: [tpope@dal.ca](mailto:th781530@dal.ca)
