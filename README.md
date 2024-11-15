# Image Stylization and Style Transfer
## Kayla Nguyen, Anastasia Nicholson, & Ashley Manzanares
This project explores the hypothesis that image stylization and style transfer techniques using famous artworks will not affect the overall recognizability and quality of the original images.

## Software & Platforms
The scripts used to clean and analyze the data were written exclusively in Python, utilizing the seaborn, pandas, and matplotlib libraries to perform time-series fitting and forecasting with the ARIMA model and develop graphs to express the results. The platform used was Windows, but the Python notebooks that contain the scripts may run on any operating system that has Python and the respective dependencies downloaded.

## Documentation Map
### DATA
This folder consists of the WikiArt image dataset that was pulled from the Deep Lake open-source package. 

There is also a Data Appendix file, which follows [this framework](https://www.projecttier.org/tier-protocol/protocol-4-0/root/data/analysisdata/data-appendixfile/) to outline and explain the process behind the variables derived in the Analysis Data File.

### OUTPUT
This folder contains any materials outputted as a result of data analysis. There were multiple figures created in the notebooks from the SCRIPTS folder:

### SCRIPTS
* exploratory.ipynb: the Python notebook used in exploratory data analysis to briefly describe the data sets and begin cleaning.

### LICENSE.md
This is the respective license for this project.

## Reproduction Instructions
1. Open the analysis.ipynb Python notebook from the SCRIPTS folder. This file has all of the necessary information to clean, process, and perform time-series fit and modeling with ARIMA on the original data sets. For this project, the .ipynb file may be opened in [Google Colab](https://colab.research.google.com/) using a GitHub link (File > Open Notebook > GitHub > [analysis.ipynb](https://github.com/anajonicholson/DS4002-Project2/blob/main/SCRIPTS/healthcare_analysis.ipynb)) or manually downloading and uploading the file into Google Colab. 

Alternatively, this can be run locally in any IDE (Visual Studio Code, IntelliJ, etc.). This operates under the assumption that the user already has a version of [Python](https://www.python.org/downloads/) downloaded onto their operating system.

1. Download the analysis.ipynb from the SCRIPTS folder.
2. Open analysis.ipynb in the IDE of choice. 
3. Run the notebook. In VS Code, there is a "Run All" button that appears in the top row of the tab where the notebook opens. There are multiple import statements and packages listed in the beginning of the notebook to acquire all dependencies. Any modules that are not on a given user's local machine may be installed with the command "pip install {module_name}" to resolve the error, which may happen with the deeplake module.

Both of these methods will produce all of the figures as seen in the OUTPUT folder as well as the model results in results.csv from the DATA folder. 

## References
[Wiki-Art Dataset](https://datasets.activeloop.ai/docs/ml/datasets/wiki-art-dataset/)
