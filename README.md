# Predicting Antimicrobial Resistance in Neisseria Gonorrhoeae Using Machine Learning 

**Author**: Anastasija Naumoski  
**Date**: April 30, 2025  
**Programming Language**: Python 3.11

# Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- python-docx

# Input Files
- `Gon data.docx` (raw MIC values and metadata)
- `cleaned_gonorrhea_data.csv` (processed MIC dataset)
  
# Output Files
- `cleaned_gonorrhea_data.csv`: Cleaned dataset after MIC value standardization
- `featureimportance.png`: Feature importance plot
- `confusionmatrix.png`: Confusion matrix visualization
- `roccurve.png`: ROC curve visualization
- `classdistribution.png`: Class distribution bar plot
  
# Description
The script loads minimum inhibitory concentration (MIC) data for Neisseria gonorrhoeae isolates from a `.docx` file, cleans and standardizes MIC values into numeric form, and defines a binary resistance outcome for ciprofloxacin. Using MIC values for seven other antibiotics, a Random Forest Classifier is trained to predict ciprofloxacin resistance. The model's performance is evaluated using a confusion matrix, ROC curve, and feature importance analysis.

