# Popular-Eurorack-Module-Dataset-2024
 
A collection of eurorack module datasets (ranging from 1000 - 8000 modules) provided as csv files from 2024. The data has been extracted from [ModularGrid](https://modulargrid.net/). <br>

### Notebooks

- <code>Generate_Dataset.ipynb</code> The scraping script used to extract data off ModularGrid. Use this if you want to create your own datasets using ModularGrid's database.

- <code>Dataset_Cleaning.ipynb</code> Attempts to clean the dataset. Merges duplicate uploads of modules, including modules that have panel descriptors (e.g. Make Noise - MATHS (black panel) is merged with the original MATHS).

- <code>Eurorack_EDA.ipynb</code> Example EDA, insight into the most popular manufactures, panel sizes, and functions.

<br>

### Attributes
- <code>Name</code> The name of the module. <br>
- <code>Manufacturer</code> Name of the company that designed the module. <br>
- <code>Functions</code> List of features that the module has been tagged with. <br>
- <code>HP</code> Size of the front panel in Horizontal Pitch, where one HP is 5.08mm. <br>
- <code>Depth</code> Distance from the font panel to the back of the module in mm. <br>
- <code>+12V (mA)</code> Current draw of the positive 12-volt rail. <br>
- <code>-12V (mA)</code> Current draw of the negative 12-volt rail. <br>
- <code>+5V (mA)</code> Current draw of the positive 5-volt rail. <br>
- <code>Price (€)</code> Set or estimated price of the module in Euros. <br>
- <code>Racks</code> Number of virtual user racks the module features in. <br>
- <code>Rating</code> A mean average of user ratings from 0-5. <br>
- <code>Votes</code> Number of users who left a rating. <br>
- <code>Available</code> Information regarding whether the module is currently being produced. <br>
- <code>Approved</code> Has the module’s specifications been approved by the manufacturer. 

<br>

Take the code with a pinch of salt, especially the Extracting and Cleaning scripts. It was put together pretty quickly for a university project, so it's just meant to get the job done, not be super efficient. Though I am confident in the quality of the datasets. Feel free to make the code better and use the data! 
