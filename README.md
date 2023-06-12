# electric_fault_detection_classification
### Read full documentation [here](https://docs.google.com/document/d/1eD4gYp8THqsm_iwLJK5Y8IjnLsoGGjG3uOxSOY7K1wM/edit?usp=sharing).

Training machine learning models to detect and classify fault in a three-phase electrical system.

* This project focuses on the detection and classification of electric faults using machine learning techniques. The project utilizes electric fault detection and classification datasets obtained from the Kaggle repository. The dataset consists of 8 attributes, including line currents (Ia, Ib, Ic), line voltages (Va, Vb, Vc), and outputs indicating the presence or absence of a fault.

* Phase 1 of the project focuses on fault detection. While phase 2 focuses on fault classification.

* The project starts with a comprehensive analysis of the dataset. Univariate analysis involves visualizing the distribution of variables through box plots and histograms. Box plots reveal outliers in current variables, while histograms provide insights into the range and count of values.

* Bivariate analysis examines the relationship between individual variables and the outputs. Histograms demonstrate the relationship between fault occurrence and current/voltage values. Additionally, a correlation heatmap highlights the correlation between different variables.

* To prepare the data for model training, preprocessing steps are applied. The dataset is split into training and test sets, and feature standardization is performed using the StandardScaler class from the Sci-kit Learn library.

* The project also extends to an electric fault classification dataset. Feature engineering is conducted to create a new target variable based on fault occurrences in different phases. Analysis of this dataset includes pie charts, statistical summaries, box plots, and a correlation heatmap.

* Preprocessing steps for the classification dataset involve label encoding of the target variable and removal of unnecessary features. Finally, one-hot encoding is applied to enable training with a neural network.

Overall, this project aims to leverage machine learning techniques to enhance the detection and classification of electric faults, providing valuable insights for improving electrical system reliability and safety.
