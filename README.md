# GLOBAL NEWS ANALYSIS WEEK 2017-2018

## Data Files:
- **Datasets**: Ensure you have extracted the 2 datasets `english_only_news-week-17aug17.csv` and `english_only_news-week-17aug24.csv` from the provided zip file `datasets.zip`. Place these files in the same directory as the project notebook for the code to run correctly.

## Environment
This project is set up with the following package versions:
- pandas: 1.4.3
- gensim: 4.3.2
- scikit-learn (sklearn): 1.3.2
- joblib: 1.2.0
- matplotlib: 3.7.2
- seaborn: 0.12.2
- numpy: 1.22.2
- nltk: 3.7
- torch: 1.11.0+cu113
- transformers: 4.36.2
- textblob: 0.17.1
- tqdm: 4.62.1
- wordcloud: 1.9.3

Ensure that your environment matches these specifications to avoid compatibility issues.

## Software Requirements

### Operating System:
- **Windows 10**

### Python:
- **Version**: Python 3.8. 

### Package Management:
- **pip**: Utilize `pip` for package installations. 

## Hardware Requirements
- **GPU:** NVIDIA GeForce RTX 3070 Laptop GPU. This project is optimized for CUDA-enabled GPUs for faster computation.

## How to Run

### Pre-requisites:
Before running the analysis, ensure that:
- Your Python environment is set up with the specified package versions.
- Your system meets the hardware requirements mentioned above.
- The datasets are extracted from the zip file and are stored at the same location as the notebook

### Instructions:
1. **Initial Setup:**
   - Do not run the introduction cells. They contain environment setup and are meant for informational purposes only.

2. **Running the Analysis:**
   - Start from the section titled **1. Data Selection and Preparation**. You can run all cells in this section until the end of the notebook.
   - The analysis is divided into three main sections:
     1. **Data Selection and Preparation:** This section includes loading the data, initial preprocessing, and setting up the data for analysis.
     2. **Exploratory Data Analysis (EDA):** Here, we perform a general analysis to understand the trends, patterns, and anomalies in the data.
     3. **Advanced Text Analysis:** This section dives deeper into text analytics, utilizing NLP techniques to extract meaningful insights from news content.

   - At the beginning of each section, the necessary packages are listed. Ensure they are installed and imported before proceeding with that section.
   - Dataframes are stored at each crucial point. This allows for rerunning specific sections independently if needed without having to process the entire notebook again.

     
### Running Time:
- **NMF and LDA Models**: Each takes approximately 2 hours and 30 minutes to run. Ensure you allocate enough time for these processes.
- **Sentiment Analysis**: Takes about 3 hours to run for the two datasets when utilizing a GPU. Ensure your system is equipped with a compatible NVIDIA GPU and the correct CUDA version to facilitate this process.
  
It's important to note that the running times are estimates and can vary based on your system's specifications and current workload. Running these processes in a system with a GPU will significantly reduce the time taken compared to a CPU-only setup.


### Note:
- Ensure you use the exact versions of the packages listed, especially for scikit-learn (sklearn). The KMeans clustering used in this project may yield different results if a different version of sklearn is used, even when setting a random seed.

By following these instructions, you should be able to run the analysis smoothly and explore the global news trends for the weeks of 2017-2018. Happy Analyzing!
