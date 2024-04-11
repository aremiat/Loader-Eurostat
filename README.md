This is a beginner version of a Eurostat loader.

The goal is to download data from their API and convert the data into a pandas data frame.

I've done three versions : 

The first one used the JSON format to import the data and then iterate through the dataset to find the codes and labels.

The second one imports the XML format and using the element tree we iterate through the dataset to find the wanted information.

The last one uses CSV format and we import only the geo code, the value, and the data.
