# OOP-Personal-Project
## Artificial Intelligence with Machine Learning in Java 2019 
Applying concepts learned in the Oracle iLearning AI with Machine Learning Course

#### Week 1 - Section 1 Introduction (4 hours)
- Read through 1.1, 1.2, 1.3, and 1.4

##### 1.2
- Goal of AI is building machines to behave intelligently
- Turing Test: if an observer of a conversation between a computer and a human cannot differentiate which one is human, then the computer passes the test.
- Artificial Intelligence: attempt to build machines capable of simulating intelligent human behavior.
- AI machines are built through the use of Machine Learning (focus of this course) or with other approaches, like Deep Learning
- Machine learning: science of getting computers to act without being explicitly programmed - Stanford University.
- ML programs aim to gain information that can be used against another similar problem.
- wiki definition- machine learning explores the study and construction of algorithms that can learn from and make predictions on data.
-Applications of AI and ML: face identification, Facebook advertisements, Netflix personalized suggestion, Amazon purchase suggestions.

###### Task - 3 scenarios that use Machine Learning
- Speech-to-text saves time typing
- Face detection/recognition improves security, reduces crime.
- GPS can avoid time spent in traffic
- Others -Virtual Personal Assistants, Video Surveillance, Online Fraud Detection, Healthcare, Financial Trading, Smart Cars

- Data Exhaust: trails of data you leave behind which constantly gives you information throughout the day
##### 1.3
- The data from users is what is feeding the growth of Machine Learning
- Data is the raw figures/facts while information is the data presented in context 
- Collection of facts (data) vs. Printing label (Information)

###### Task - Data or information
All student marks- Data
Average of student marks- Information
Country of all visitors to a website- Data
Total visitors to a website by country - Information
Total sales by day- Information
Time and data of a sale transaction- Data
Student data on an enrollment form- Data
Student address on a label- information

##### 1.4
- Machine Learning : "intelligent machines" are all ran by algorithms and require input of some form to learn (voice, files, internet searches, electronic instruments, etc.)
- ML algorithms are split into two categories : supervised and unsupervised learning
- Supervised learning : occurs when information is available, but not enough information to learn until more data is gathered. There is a known label(property or result set) that can feed it data from a training set (data). Examples: loan approval decision based on dependent data like age, credit rating, etc, or an email spam filter which asks you to report spam. Training data ("learning") and test data (accuracy) are used to improve the algorithm which is called generalization.
- Generalization (ability of an algorithm to be generalized to new data) and Overfitting (when a model is trained too well on training data and is unable to generalize.
- https://wp.wwu.edu/machinelearning/2017/01/22/generalization-and-overfitting/
- Goal - produce good test data for the generalization models, while maintaining flexibility with new data
- Independent data (predictors used to determine target/outcome) vs. dependent data (target/outcome of application is dependent on independent data)
- Supervised Learning: data stored in a label falls into these two categories
- Classification -independent data is defined as a class label with a discrete value, output variable is a category. The prediction data (dependent data) is output.
- Regression -output variable is a real value such as "dollars" or "weight" (https://www.geeksforgeeks.org/regression-classification-supervised-machine-learning/)
- ranges of data stored using real numbers, continuous not discrete
- Predictions from regression range could also be a range rather than a closed set
- In many cases you can change a regression to classification
- Supervised learning and Structured Data are focused on in this course

- Unsupervised Learning - structure of data is unknown, no known labels or classifications. These algorithms make inferences typically from big datasets.

###### Task
- Temperature - 26,24,23,26 Regression
- Age - 22,45,22,30 Regression
- Age - Young, Middle, Old Classification
- House Value - 100000,150000,120000 Regression
- House Value - Low, Middle, High, Very High Classification
- Animal - Cat, Dog, Fish Classification
- Eye color- Blue, Green, Brown Classification

- Structured data -high degree of organization with each item fitting into a type. Ex. numbers, dates, normally displayed in table format  
- Unstructured Data -data that does not conform to the rules of Structured Data. Ex. email message, text, pictures, multimedia messages, sound

- Steps to look at Structured Data
- Collect input and result examples
- Make a model from the examples
- Add new inputs (test data) to the model
- Test the results (outputs) from the model and evaluate 

###### Task
1. Examples of classification: Age, Has Job, Owns House, Credit Rating
2. Young, No, No, Fair
3. Dependent data is determined by the independent data, so the classifications of age, has job, owns house, and credit rating are used to determine a loan approval for rows 3,5, and 6.

- Labels (classifications) - composed of both independent and dependent data

##### 2.1 
