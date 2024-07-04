# SMS-spam-Detection
Abstract:
SMS spam detection is crucial in telecommunications for identifying and filtering out unwanted messages sent via text messaging services. The goal is to distinguish between legitimate messages and spam messages, which often contain fraudulent schemes or unwanted advertisements. This process involves leveraging machine learning techniques trained on labeled datasets to automatically classify incoming messages based on their content and linguistic features. Effective SMS spam detection helps protect users from potential scams and enhances the overall user experience with mobile communication services.

Methodology:

1. Data Collection:

Gathering a diverse dataset of SMS messages, including both spam and non-spam (ham) messages,ensuring that the dataset is labeled to indicate whether each message is spam or ham.

![Dataset jpg](https://github.com/Shreyshukl/SMS-spam-Detection/assets/158249360/22420f70-b868-49d7-873f-1cd3dcdf8006)

2. Exploratory Data Analysis:

EDA is a crucial initial step in data analysis, where the primary objective is to understand the data and its characteristics before applying any modeling or statistical techniques.

![EDA](https://github.com/Shreyshukl/SMS-spam-Detection/assets/158249360/8148ff92-12a3-4e3b-a968-e2b10571a0c0)

After analysis we found out that our dataset was heavily imbalanced

3. Preprocessing:
   
.Cleaning the text data by removing punctuation, special characters, and stop words.
.Normalize the text by converting all letters to lowercase.
.Tokenize the text into individual words or tokens.
 
  ![WordCloud](https://github.com/Shreyshukl/SMS-spam-Detection/assets/158249360/b4914ef8-11e2-4abd-8dc4-ab1efaa546ba)

4. Result:

   Using Naive Bayes Machine Learning Algorithm for SMS-spam-Detection on the provided dataset.
   ![Naive_bayes](https://github.com/Shreyshukl/SMS-spam-Detection/assets/158249360/1addf292-97e9-44dc-856d-851fa6e03626)

   ![best_result](https://github.com/Shreyshukl/SMS-spam-Detection/assets/158249360/42845c47-b1ae-4323-84d9-59e5b3f951d8)










Use techniques like TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical feature vectors.
