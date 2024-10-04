#Udacity Disaster Response Pipeline Project

This project focuses on analyzing disaster-related data from Figure Eight to develop an API model capable of classifying disaster messages. The dataset includes real-world messages sent during various disaster events. A machine learning pipeline is constructed to categorize these messages, ensuring they are directed to the appropriate disaster relief organization.

Additionally, the project features a web application where emergency responders can input new messages and receive classification results across different categories.

### Step Instructions:
To initialize your database and model, execute the following commands from the root directory of the project:

1. To run the ETL pipeline that processes and stores the cleaned data: python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db

2. To execute the machine learning pipeline that trains the classifier and saves the model: python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

3. In the application directory, use this command to launch the web application: python run.py

4. Open your browser and navigate to: http://0.0.0.0:3001/