### Question 1: Genetic Algorithm for Intrusion Detection

**Overview:**
Implementing the Genetic Algorithm on the UNSW-NB15 dataset for intrusion detection, based on the paper "An Evolutionary Approach to Intrusion Detection System using Genetic Algorithm".

**Base Paper:**
You can find the details of the Genetic Algorithm implementation in the provided paper.

**Base Code:**
The official implementation of the paper can be found [here](https://github.com/daffidwilde/edo-paper/tree/main?tab=readme-ov-file).

**Dataset:**
The dataset (UNSW-NB15) contains raw network packets and includes various types of attacks such as DoS, worms, Backdoors, and Fuzzers.
https://www.kaggle.com/datasets/dhoogla/unswnb15/data

**Requirements:**
1. **Experiments:** Conduct at least three experiments by varying parameters like population size, crossover type, etc., to gain insights into their effects on the algorithm's performance.
2. **Code:** Provide a zip folder containing all code files with a clear and simple Python run file.
3. **Report:** Include a concise report detailing the experiments in a tabular format, matching the evaluation parameters of the base paper. Also, provide insights into the choices made during implementation, such as the selection of fitness functions.

**Confusions Clarified:**
1. **Fitness Function:** You are free to use any relevant fitness function, not necessarily the one mentioned in the base paper.
2. **Code Modifications:** You can make necessary changes to the base code for dataset compatibility, but ensure these changes are relevant and documented in the report.

### Question 2: Multi-Variant Linear Regression on Personal Routine Dataset

**Overview:**
Implementing Multi-Variant Linear Regression on a self-created dataset representing a 20-day routine, with independent variables like sleep hours, food quality, working hours, health condition, and mood, and a dependent variable representing productivity rank.

**Requirements:**
1. **Data and Code:** Provide a zip folder containing the dataset and code files.
2. **Model Implementation:** Implement Multi-Variant Linear Regression with Gradient Descent from scratch, without using any libraries.
3. **Data Scaling:** Fill the data values between 1 to 10.
4. **Random Initialization:** Randomly initialize parameters like slope (m), intercept (c), and the number of epochs.
5. **Exploratory Data Analysis (EDA):** Perform EDA and interactive data visualization, including scatter plots for original data, correlation analysis, accuracy plots, best fit line plots at each epoch, gradient descent visualization, and epoch vs. loss plots.
