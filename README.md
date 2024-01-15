# London-in-Data-Biking-Trails-and-Weather-Tales

## Snippet:
### **Data Analysis in Jupyter environment** 

![image](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/599f2d17-7b41-44bb-a070-d2697012268e)

### **Data Visualization using Tableau**

![Dashboard 1](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/e2fab66d-5cec-40c5-86b9-3afdf6a03777)

## Data extraction, Data pre-processing and Data analysis 
First, I began by installing essential libraries such as pandas, zipfile, and Kaggle. If an error occurs during downloading, it may indicate that these libraries are not installed on your device, so you can install them using commands like “!pip install Kaggle” followed by “import Kaggle.”
![image](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/f1b3ac08-4fd1-44a8-8f53-07d08e9f9410)

Next, to download the dataset from Kaggle, obtain your Kaggle API key by navigating to your Kaggle profile, selecting 'Settings', and under the 'API' section, clicking on 'Create New API Token.' Ensure you place the API key file in the appropriate system directory as required by your specific editor or environment.
![image](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/9685f291-4725-4d25-afc4-dd1dda3bc906)

Once the dataset is loaded into your notebook or environment, begin with Exploratory Data Analysis (EDA). EDA is the process of investigating datasets to uncover patterns, anomalies, and insights, primarily through statistical graphics and visual methods. My step-by-step process includes using `.info()` to get a concise summary of the DataFrame, `.shape` to understand its dimensionality, and `.value_counts` to analyze the frequency of unique values. If column names in the dataframe are not self-explanatory, consider renaming them for clarity using a dictionary in Python.
![image](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/b738646d-aab4-4dca-8d2a-797bac89941d)

For instance, I converted the scale of humidity from 1 to 100 to a more intuitive 0 to 1 scale, making it easier to interpret as percentages, where 0.2 represents 20% and 1 represents 100%. Additionally, I employed dictionaries like `season_dict` and `weather_dict` to map numeric codes to descriptive labels, transforming the 'season' column from numerical values to readable season names such as 'spring', 'summer', etc.
![image](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/c754a57b-fcc2-4c3a-90ca-f9750eb724be)

After refining the data for better readability, you can import it into visualization tools like Excel, Tableau, or Power BI. For this project, I chose Tableau for its robust data visualization capabilities. Feel free to experiment with more EDA as per your requirements and experience.

## Data Visualization in Tableau 

For the visualization aspect, I delved into creating new calculated fields, parameters, and bins to enhance the dashboard's analytical depth.

The use of calculated fields allowed for the derivation of new insights from existing data, while parameters provided interactive controls for end-users, enabling them to explore data variations dynamically. Bins were instrumental in segmenting data, making it easier to discern patterns and trends. This combination of techniques resulted in a dashboard that stands out for its explicitness and detailed representation of data.

A key component of this project was the careful selection of the color scheme. The right color palette not only makes the dashboard aesthetically pleasing but also plays a significant role in conveying the data narrative clearly and effectively. 

![Dashboard 1](https://github.com/prayagpadwal/London-in-Data-Biking-Trails-and-Weather-Tales/assets/65147413/e2fab66d-5cec-40c5-86b9-3afdf6a03777)
