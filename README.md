
# Machine-Learning-IMR Review with Medical Necessity Model
## Objective
Objective: To leverage machine learning to predict the possibility of medical services to be deemed medically necessary or not based on the presence of certain conditions.

Dataset: [Kaggle](https://www.kaggle.com/datasets/prasad22/ca-independent-medical-review)
<img width="975" alt="Screen Shot 2023-07-03 at 11 41 31 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/88ba071e-c83d-4656-91ee-34cce915a722">

# Database Setup
## SQL and CSV Export 
<img width="580" alt="Screen Shot 2023-07-03 at 11 42 53 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/55f1ca95-c8b8-4886-8ac1-4f0f5a5e16cc">
<img width="360" alt="Screen Shot 2023-07-03 at 11 43 11 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/91f355df-b5a1-4c90-b11b-152d7efa95cd">

# Machine Learning Models

## "Type" Machine Learning Model 

### Installation/Dependencies
```bash
import numpy as np 
import pandas as pd 
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
import tensorflow as tf
from sklearn.metrics import balanced_accuracy_score, confusion_matrix, classification_report
```
## Roadmap

- Install Dependencies 

- Upload CSV file for kaggle dataset and create dataframe

- Find Unique Values 

- Find Value Counts for "type"
 
- Bin "Not Medically Necessary"

- Bin "Investigational/Experimental and Urgent Care" 

- Set "type" as target

- Drop Type 

- convert category data into numerical to create pd.get_dummies

- Split preprocessed data into our features and target arrays 

- Split the preprocessed data into a training and testing dataset 

- Create StandardScaler Instances 

- Fit StandardScaler 

- Scale the Data 

### Testing a deep neural network 
<img width="627" alt="Screen Shot 2023-07-03 at 11 45 41 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/c932f5c8-a6d7-4e50-ae2e-b9bfb747b574">
<img width="461" alt="Screen Shot 2023-07-03 at 11 46 34 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/ab81569c-8a46-4047-9518-86d80b6d4270">

### Testing Logistic Regression 
<img width="389" alt="Screen Shot 2023-07-03 at 11 47 19 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/4b55dcc0-cb3d-497b-a045-5498e3d3ab3c">
<img width="390" alt="Screen Shot 2023-07-03 at 11 47 33 AM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/1008dfd7-cf13-4082-b1ce-7a1a840e92a3">

### Testing Logistic Regression after Over Sampling the Data
<img width="415" alt="Screen Shot 2023-07-03 at 12 11 10 PM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/23a1fec3-ccfd-458e-91a2-9e31f1fdcfc1">
<img width="368" alt="Screen Shot 2023-07-03 at 12 11 23 PM" src="https://github.com/Phil-Mart/healthcare-machine-learning-model/assets/120279988/1a7491cb-414c-49b4-ba71-3f3a4c70ac1e">

# Analysis 

### Objective: To leverage machine learning to predict the possibility of medical services to be deemed medically necessary or not based on the presence of certain conditions.

### Conclusion: We found that majority of insurance denials, once appealed by an IMR, were overturned and therefore considered as converage that should be paid by an insurance company. This, in conclusion, eludes to large miscalculations by the health insurance industry across the State of Califoria. With a simple set of machine learning models (like the ones we have developed), companies can quickly and effectively reduce the number of coverage denials they will have issued destined to be overturned, thus saving them the significant costs of litigation and additional payments to urgentcare facilities. This, we believe, is a business strategy worth implementing immediately to save money on the bottom line and provide more coverage to its customers.

### Presentation:[Analysis Presentation](https://docs.google.com/presentation/d/1WFbteX6ApynYJe-QSTuQRjewO7j6qurs/edit?usp=sharing&ouid=100163998019227497445&rtpof=true&sd=true)

### Visualizations:[Tableau Storyboard](https://public.tableau.com/views/IRMUrgentCareVisualAnalysis/VisualizationAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)

Our orignal question for this dataset was asking "Why does it feel like Urgent Cares are popping up everywhere?" With this dataset, We can see Urgent Cares are more affordable than Hospitals. This data shows more cost effectiveness as we can see an overwhelming amount of data showing how often care is not considered a medical necessity and will require an additional payment. 
Why are Urgent Cares Popping Up Everywhere? 
[CNN Article](https://www.cnn.com/2023/01/28/business/urgent-care-centers-growth-health-care/index.html#:~:text=Urgent%20care%20has%20grown%20rapidly,increase%20from%202019%2C%20estimates%20IBISWorld.)



# Authors 
Phillip Martinez[github](https://github.com/Phil-Mart)

Kayla Bailey [github](https://github.com/baileykayla953/Machine-Learning-)

Dhawn Alexander [github](https://github.com/DhawnAlexander)

Jason Didier [github](https://github.com/CRC1990) 




