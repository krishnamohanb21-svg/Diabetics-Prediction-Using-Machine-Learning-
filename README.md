# Diabetics-Prediction-Using-Machine-Learning-
# Problem Statement :
Diabetes is a serious medical condition found in millions across the globe. Early diagnosis will help control and treat
the illness effectively, alleviating complications as well as helping improve patient prognosis. The target of this
machine learning project is to create an accurate predictive model that can well determine if one is diabetic through a
given collection of clinical as well as demographic attributes.
There are patient records with the given features:
Demographic characteristics: 
Gender, Age Symptoms and clinical indicators: Polyuria, Polydipsia, Sudden Weight Loss, Weakness, Polyphagia, Genital Thrush,
Visual Blurring, Itching, Irritability, Delayed Healing, Partial Paresis, Muscle Stiffness, Alopecia, Obesity
Target variable: Class (diabetic or non-diabetic)


# Proposed System of Diabetics Prediction Using Machine Learning
The system will predict whether a patient will have diabetes or not based on the features mentioned in the dataset, including Age, Gender, Polyuria, Polydipsia, etc. The solution will include collecting data, preprocessing it, training machine learning algorithms, deploying the model, and measuring its performance.1. 

# 1.Data Collection
Historical Data: The data would be patient records with details of their age, gender, symptoms (e.g., polyuria, polydipsia), and other clinical characteristics, including the class label (diabetic or non-diabetic).
example dataset attributes:
Age: Patient's age. 
Gender: Patient's gender. 
Polyuria: Frequent urination (binary: Yes/No). 
Polydipsia: Excessive thirst (binary: Yes/No).
Sudden weight loss: Loss of weight without effort (binary: Yes/No).
Weakness: Lack of energy or fatigue (binary: Yes/No).
Polyphagia: Increased hunger (binary: Yes/No). 
Genital thrush: Symptoms of fungal infection (binary: Yes/No). 
Visual blurring: Blurry vision (binary: Yes/No).
Itching: Skin irritation (binary: Yes/No). 
Irritability: Feeling of easy annoyance (binary: Yes/No). 
Delayed healing: Slowness of wound healing (binary: Yes/No). 
Partial paresis: Weakness of muscles or partial paralysis (binary: Yes/No). 
Stiffness in muscles: Rigidity or unflexibility in muscles (binary: Yes/No). 
Alopecia: Baldness (binary: Yes/No). 
Obesity: Overweight condition (binary: Yes/No). 
Class: Target variable, 1 for diabetic and 0 for nondiabetic.
Real-time Data: Depending on availability, other features such as patient lifestyle, diet, and exercise may be added to enhance model precision.

# 2. Data Preprocessing
The data must be cleaned and preprocessed prior to feeding it into the machine learning algorithms:
Preprocessing steps:
Handle Missing Values: Detect and fill missing values or drop rows with considerable missing data.
Convert Categorical Features to Numerical: Features such as Polyuria, Polydipsia, Gender, and others may need to be encoded (e.g., Yes = 1, No = 0).
Feature Scaling: Scale continuous features such as Age and Obesity via normalization or standardization (e.g., Min-Max scaling or Standard Scaler).
Split the Data: Split the data into training and testing sets, typically an 80/20 split (80% training, 20% testing).

# 3. Machine Learning Algorithm
There are various machine learning models that can be employed to predict if an individual has diabetes from the given features:
Logistic Regression: An easy-to-use and efficient algorithm for binary classification.
Decision Trees: Can facilitate visualization of the decision-making process.
Random Forest: An ensemble technique that tends to improve over decision trees.
Support Vector Machine (SVM): A strong algorithm for binary classification problems.
K-Nearest Neighbors (KNN): A non-parametric algorithm that classifies by proximity to closest data points

# 4. Deployment
After you have trained a model that works well, you can deploy it in a real-world application.
User Interface: Design a web interface where users can enter their details (e.g., Age, Gender, Polyuria, Polydipsia sudden weight loss weakness Polyphagia Genital thrush visual blurring Itching Irritability delayed healing partial paresis muscle stiffness Alopecia Obesity etc.) to predict if they have diabetes.
Use Flask for designing the web interface.
The app will accept the user input, feed it into the model, and output a prediction (e.g., diabetes risk = "Yes" or "No").

# 5. Evaluation
Once deployed, continuously evaluate the performance of the model. Use metrics such as:
Accuracy: It measures the ratio of correct predictions.
Precision: It measures how many of the predicted positive cases (diabetic) are indeed positive.
Recall: It measures how many actual positive cases were picked up by the model.
F1 Score: Harmonic mean of precision and recall.

# 6. Result
The last output is a system that predicts whether an individual is likely to have diabetes given their clinical features. The deployed system enables the user to feed in their details and receive real-time prediction for their risk of diabetes.

# System Requirements 
HARDWARE REQUIREMENTS :
The hardware requirements for running this website and model  are:
RAM – 8.00 GB
Operating System – Windows 11 
Processor – Intel(R) Core(TM) i3-1115g4
Processor speed – 3.00 GHz
SOFTWARE REQUIREMENTS: 
The programming language used to develop this application is Python and the IDE used is Jupyter Notebook. Front end is made using HTML and is integrated with  flask.
Programming Language – Python
Python IDE – Jupyter Notebook
Python Libraries: Flask

# Libraries to build the model
1)Pandas 
2) matplotlib
3) seaborn 
4) sklearn 
5) Flask

# Results
<img width="923" height="841" alt="image" src="https://github.com/user-attachments/assets/2963f83c-904d-429f-8ede-8432c3c4edc3" />
<img width="913" height="855" alt="image" src="https://github.com/user-attachments/assets/93c985be-d4f8-4851-867e-7fb67d9e232b" />
<img width="1092" height="796" alt="image" src="https://github.com/user-attachments/assets/fa23ed88-54bd-4557-bbfb-4f749dc245eb" />
<img width="850" height="796" alt="image" src="https://github.com/user-attachments/assets/7a18d0f4-2fba-4b9f-a9aa-3069d5a6df64" />
<img width="1022" height="944" alt="image" src="https://github.com/user-attachments/assets/c70fb632-fd54-4a32-82c9-d83fb26f130a" />
<img width="915" height="864" alt="image" src="https://github.com/user-attachments/assets/ee4241fc-66ec-45dd-a7b3-eb6cb1cb701f" />
<img width="1012" height="1066" alt="image" src="https://github.com/user-attachments/assets/37c39acf-12c0-472e-aaa2-149e18b80233" />
<img width="945" height="231" alt="image" src="https://github.com/user-attachments/assets/0cd2b43b-c101-4290-a3a0-e83c54d46e4b" />
<img width="945" height="818" alt="image" src="https://github.com/user-attachments/assets/9c2c12cf-1d8e-4c96-901e-1dfceebc9b33" />
<img width="1085" height="1031" alt="image" src="https://github.com/user-attachments/assets/da14020b-2adc-434e-870a-6749de591a7f" />
<img width="1027" height="942" alt="image" src="https://github.com/user-attachments/assets/f3c8721e-7ea2-4750-8c35-0eb9f69e923b" />
<img width="1455" height="997" alt="image" src="https://github.com/user-attachments/assets/07ddf4e5-0557-4c2a-ade3-3585c88dcd03" />

# Algorithm 
1) Logistic Regression
2) Decision Tree Classifier 
3) Support Vector Machine
4) Random Forest Classifier 
5) K nearest -Neighbors Classifier

# Logistic Regression
This is the one of the most common model used in ML ,Logistic Regression is often applied in the actual manufacturing context the fields such as data mining, automatic disease diagnosis and economic prediction. For our model,   use Logistic regression to know the risk factors for heart disease and forecast the probability of disease    occurrence based on risk factors. This model is most frequently applied for classification, primarily two-category issues (that is, there are only two types of output, each representing one category), and can indicate the probability of occurrence of each classification event. Logistic regression model is shown below: This technique used is also known as sigmoid function .Sigmoid function helps in the easy representation in graphs. Logistic regression also provides better accuracy. By using equation the logistic regression algorithm is represented in the graphs showing the difference between the attributes.
Where Y refers to binary dependent variable (Y is equal to 1 if event happens; Y=0 otherwise), e stands for the foundation of natural logarithms and Z  means
with constant β0 ,coefficients β j and predictors X j , for p  predictors(j=1,2,3,.....,p)
with constant β0 ,coefficients β j and predictors X j , for p  predictors(j=1,2,3,.....,p)
The process of modeling the probability of a discrete outcome given an input variable is known as the Logistic Regression. The most common logistic regression, as its name suggests is not regression rather it is a classification algorithm that classifies something that can take two values such as true/false, yes/no, and so on. Logistic regression identifies a hyperplane in a manner that when it is passes through a function whose value ranges between 0 and 1 (typically we use sigmoidal), it optimizes cost function. Bases on closeness to 0 or 1, it predicts a Boolean output. Here vector parameters is used for training. σ(.) is usually a sigmoid function, with output between 0 and 1.

# Features of Logistic Regression 
Multinomial logistic regression is the type of regression which uses the softmax function to compute probabilities.
● We use loss function to learn weights(vector w and bias b) from a labeled training. we perform such activity to minimize the cross-entropy loss.
● Iterative algos like gradient descent are used to get the weight(optimal).while minimizing the loss function the type of convex optimization problem.
● To avoid overfitting regularization is used.
● Logistic regression has the ability to transparently study the importance of individual features.

#  Advantages  and Disadvantages of Logistic Regression 
Advantages 
● This technique is perform well and fast where we have to classify unknown records.
● This is not limited to binary classification we can easily extend it to  multinomial regression.
Disadvantages 
● Logistic regression will not perform well If the number of observations is lesser than the number of features in such condition it may lead to overfitting.
● Logistic regression constructs the linear boundaries. In the logistic function equation, x is the input variable. Let's feed in values −20 to 20 into the logistic function. As illustrated in Figure the inputs have been transferred to between 0 and  1.
<img width="1492" height="809" alt="image" src="https://github.com/user-attachments/assets/af6f0120-8379-45dc-9bf5-dcdbcfd15b01" />
<img width="1229" height="813" alt="image" src="https://github.com/user-attachments/assets/fae87e49-781a-4eec-b70b-6237aadee63a" />
<img width="701" height="753" alt="image" src="https://github.com/user-attachments/assets/5e60519c-9ad9-4b2b-b9a6-9ca3f82670a6" />
Accuracy 91.67 %

# Decision Tree Classifier 
A decision tree contains a flowchart-like structure. In the structure of DT(Decision Tree) in a test, an attribute is represented using an internal node. The result of the test is represented using the branch. To represent a class label, a leaf node is used. To represent classification rules paths from root to leaf are used. This is the type of analysis in which closely related influence diagrams are used for a visual and analytical root. Where the expected values of competing alternatives are calculated.
Architecture of Decision Tree.
<img width="790" height="444" alt="image" src="https://github.com/user-attachments/assets/970b6237-8583-415b-a580-4f199335c71e" />
<img width="1839" height="887" alt="image" src="https://github.com/user-attachments/assets/408bd799-4ddd-4ba0-b5c6-d38e22120ba7" />
<img width="1229" height="786" alt="image" src="https://github.com/user-attachments/assets/f02c93f8-2f64-4820-a1de-f5fb872723c6" />
<img width="671" height="772" alt="image" src="https://github.com/user-attachments/assets/4b081a00-d69f-4581-8e6c-e8922afd8581" />
Accuracy 95.51 %

#  Support Vector Machine
Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and regression tasks. It works by finding the optimal hyperplane that best separates data into different classes. The main goal of SVM is to maximize the margin between different classes while minimizing classification error.
Features of SVM 
1.Margin Maximization: SVM finds the hyperplane that maximizes the margin between classes, which helps improve generalization and robustness.
2.Support Vectors: Only a few important data points (called support vectors) are used to define the hyperplane, making the model efficient.
3.Effective in High Dimensions: SVM performs well even when the number of features is very large (high-dimensional spaces).
4. Kernel Trick: Allows SVM to solve non-linear classification problems by transforming the input data into higher-dimensional space using kernel functions (e.g., RBF, polynomial).
5.Versatile: Can be used for binary as well as multi-class classification problems. 
6. Regularization: SVM includes a regularization parameter (C) that balances the trade-off between maximizing the margin and minimizing the classification error.
7. Robust to Overfitting (in high-dimensional space):Due to its focus on margin and support vectors, SVM can generalize well, especially when data is not too noisy.
<img width="1882" height="812" alt="image" src="https://github.com/user-attachments/assets/19846b52-3275-434e-a815-5bf2c38dff9e" />
<img width="1225" height="821" alt="image" src="https://github.com/user-attachments/assets/ed32b1a8-1ada-4acc-b50c-bd700cc7144c" />
<img width="606" height="732" alt="image" src="https://github.com/user-attachments/assets/71faa1ef-1559-4c79-8fbb-cc6b8ea42e6c" />
Accuracy 91.67 %

# Random Forest Classifier
A Random Forest Classifier is a method of ensemble learning applied to classification problems. It constructs multiple decision trees and combines their predictions to enhance accuracy and avoid overfitting. Each tree is trained on a random subset of data and attributes, hence making the model stable, robust, and effective in handling complex datasets.
<img width="840" height="546" alt="image" src="https://github.com/user-attachments/assets/6be52aa2-a0c7-48b2-84c0-ff85f2d807fc" />

# Features of Random Forest 
●	It runs Efficiently in scenarios where database is very huge.
●	We can perform classification on Thousands of Input variables.
●	Using this we can find which variable is useful for our classification.
● Using this we can easily calculate the missing data and also maintain the good accuracy. Even though it has missing data.
<img width="1321" height="1016" alt="image" src="https://github.com/user-attachments/assets/66896501-08ad-4a15-af9d-98d6094ed11a" />
<img width="1234" height="786" alt="image" src="https://github.com/user-attachments/assets/c0596920-50fa-4398-80a0-2c706edc86d5" />
<img width="701" height="773" alt="image" src="https://github.com/user-attachments/assets/37a0ee59-15e7-4c97-aef6-edab9dfbb41b" />
Accuracy 95.51 %

#  K-Nearest Neighbors 
K-Nearest Neighbors (KNN) is a classification and regression online (lazy) learning algorithm. It's a non-parametric approach to the extent that it doesn't make any assumption regarding the distribution of the data.
How It Works:
Input Data: To predict a given new data point, KNN computes the similarity between this data point and the entire training data set.
Distance Metric: Any distance metric such as Euclidean, Manhattan, or others can be employed based on the problem.
Finding Neighbors: It finds the k training samples nearest to the input point.
Prediction: For classification, the most common label among the k neighbors is returned. For regression, the mean value of the k neighbors is taken as the prediction.
Model Training & Prediction (Using sklearn):
Training: Employ the fit() function of K Neighbors Classifier or KNeighborsRegressor from sklearn .neighbors.
Prediction: Employ the predict() function on the test set.
Selection of k value:
Selecting k (number of neighbors) is important:
A low k may produce overfitting (high variance).
A high k can smoothen the decision boundary but may lead to underfitting (high bias).
For selection of the best k, vary k and check the model performance using cross-validation.
The location at which adding k no longer further enhances accuracy appreciably is referred to as the knee point.
<img width="1546" height="580" alt="image" src="https://github.com/user-attachments/assets/4b2389cc-179f-429a-b0d0-c393d11401ca" />
<img width="1044" height="752" alt="image" src="https://github.com/user-attachments/assets/fd8f068c-37f9-441f-9fec-56811b1890a8" />
<img width="759" height="735" alt="image" src="https://github.com/user-attachments/assets/af4a9b21-835c-45b7-9385-bb245ff0941f" />
Accuracy 83.97 %
<img width="1386" height="285" alt="image" src="https://github.com/user-attachments/assets/1c4afcce-3573-4518-aaa3-00e40f72efe9" />

# Deployment (Working model Diagram)
<img width="1093" height="714" alt="image" src="https://github.com/user-attachments/assets/ffbc8c36-9529-4c0f-b508-deb5198ba1e5" />
<img width="842" height="714" alt="image" src="https://github.com/user-attachments/assets/99f16bfa-8c73-435c-8556-a947612a605c" />
<img width="1806" height="855" alt="image" src="https://github.com/user-attachments/assets/60be65f7-d136-4c44-b03a-eef5d3d17025" />
<img width="1055" height="714" alt="image" src="https://github.com/user-attachments/assets/56fbad79-722b-4a74-8aa6-c823a59c8f03" />
<img width="903" height="702" alt="image" src="https://github.com/user-attachments/assets/c0ff53fb-b4f2-4f72-bbbb-04843a8b5dc8" />
<img width="1718" height="921" alt="image" src="https://github.com/user-attachments/assets/76f831bf-eb09-4730-8280-e7a8ef23f683" />

# Conclusion
This project investigated the application of machine learning models to forecast diabetes from principal demographic and symptomatic predictors such as age, gender, and typical diabetes symptoms like polyuria, polydipsia, sudden weight loss, and visual blurring. With a labeled dataset containing these features, multiple classification models were trained and tested for their power to correctly separate diabetic and non-diabetic individuals.
The findings show that machine learning has the potential to be an effective tool for the early diagnosis of diabetes, particularly when clinical data is symptom-dense and well-organized. Of the models evaluated, [best-performing model] was the most accurate, precise, and recallable, showing that it is efficient in detecting patterns highly correlated with the onset of diabetes.
This method can potentially assist healthcare professionals in providing faster and more precise diagnoses, especially in low-resource environments. Future research can include the integration of laboratory values (e.g., blood glucose), real-time data integration, and deployment of the model into user-friendly applications for broader clinical application.

# Future Scope
The existing machine learning strategy for diabetes prediction using demographic and symptom-related features has yielded promising results. Yet, there are a few directions open for future development and usage: 
Inclusion of Clinical and  Biochemical Data: While the model employed here is based on self-reported symptoms and elementary demographic data, incorporating clinical data like blood glucose, HbA1c, and insulin response could substantially enhance predictive ability.
Early-Stage Screening Tools: The symptom-based model can be extended to low-cost, low-tech screening tools for early-stage detection of diabetes, particularly in rural or underprivileged regions where laboratory facilities are not easily accessible.
Model Generalization and Validation: Increasing the dataset to cover a more diverse population in terms of ethnicity, age groups, and geography can enhance model robustness and generalizability.
Hybrid Models: Blending symptom-based prediction with lifestyle characteristics (e.g., dietary patterns, exercise, familial history) may result in more integrated and individualized risk estimations.
Mobile Health Applications: The developed model may be applied in mobile applications or chatbots to give immediate diabetes risk feedback based on user-inputted symptoms.Temporal Analysis and Risk Progression: Analyzing symptom progression through sequential or time-series models would enable the prediction not only of presence but also of diabetes stage or severity.
Explainability and Trust: The use of explainable AI (XAI) can explain how individual symptoms (such as polyuria, alopecia) contribute to the ultimate prediction and establish trust between clinicians and patients.
















 













