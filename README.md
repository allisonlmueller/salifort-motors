# Salifort Motors Employee Retention Project
Google Advanced Data Analytics Capstone Project
### Overview
The goal of this project was to construct a decision tree and random forest model to predict employees that are likely to quit the fictional company Salifort Motors, in the hope that this will reveal the factors that contribute to employees leaving. The final decision tree model achieved an AUC score of 95.9% and accuracy of 95.9% in predicting which factors contributed to exployees leaving. Based on the model, the features that contributed most to employees leaving the compnay were score of last evaluation, number of projects, tenure, and if they are overworked.
### Business Understanding
The HR department of Salifort Motors conducted a survey to collect information from their employees about satisfaction with the company. Now that they have the data, they want to take some initiatives to increase employee satisfaction and hopefully find ways to improve employee retention.
### Data Understanding
This project utilized a fictional dataset that represented self-reported information from employees of a fictitious multinational vehicle manufacturing company. The data consisted of 14,999 unique observations and 10 features. Features in this dataset include information on employee satisfaction levels, their role in the company, how much they work, and whether they have left the company. Approximately 17% of employees left the company, and 83% stayed. Related to this, a feature was engineered to represent if an employee was overworked or not. Multiple redundnant columns were dropped and some were reformatted into the proper data type for modeling.
### Modeling and Evaluation
A decision tree model and random forest were used to determine feature importance to predict factors that would contribute to employees leaving the company. After constructing both models, the decision tree model slightly outperformed the random forest model. The overall model performed with 95.9% accuracy and 95.9% AUC in determining who will leave the company. The plot below shows that the top four factors contributing to an employee leaving are last evaluation score, number of projects, tenure, and if they are overworked.

<img width="513" alt="Screenshot 2023-10-06 at 5 29 28 PM" src="https://github.com/allisonlmueller/salifort-motors/assets/147258601/929c5b0f-8e25-498d-b745-7302eeeb2ca1">

### Conclusion
This model can benefit the HR department of Salifor Motors by providing them with the factors that have the greatest influence on employee satisfaction and if they remain at the company. Some recommendations for Salifort Motors are to promote employees with the longest tenure, reward employees for working overtime, reduce the number of projects each employee is tasked with, and to hold company-wide meetings about culture to gain insight on even more areas for improvement. In the future, analysis should be done specifically on employees with a 4-year tenure because they seem to be the most dissatisfied.
