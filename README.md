# Hotel_Booking_DB-Big-Data-Analysis-Report
Politecnico di Milano - Prof. Marco Brambilla - System and Methods for Big and Unstructured Data
<br><br>
Final Grade: 30 Cum Laude / 30
<br><br>
The aim of this project was to analyze a database regarding booking cancellations across various hotels in Germany. I produced a report where I analyzed the data through various queries in MongoDB, a NoSQL database chosen for its flexibility and scalability with large volumes of data. The analysis is both predictive and prescriptive and it's designed to be useful to the hotel business for implementing measures aimed at increasing profits.<br><br>
The database was taken from the website kaggle.com. Initially, I conducted a preprocessing phase to clean the data, making it easier to understand and query in MongoDB. The database was in .csv format, so I utilized the Pandas library for all the Data Wrangling tasks. Then I started the proper analysis performing multiple queries, as described in the documentation.<br><br>
I have also trained a simple neural network in TensorFlow with the intention of interpreting it using the SHAP method (SHAP library, Python), which is one of the most common XAI technique (Explainable Artificial Intelligence). This is interesting because it highlights which features are useful and which are not, helping hoteliers identify and profile customers. As often happens, in this case too, a few important features carry most of the predictive power.

Here we can see an example of one interesting query and its result.

![Screenshot 2024-03-12 alle 22 26 27](https://github.com/Davide-Ettori/Hotel_Booking_DB-Big-Data-Analysis-Report/assets/52358285/c2e23fb4-499a-4b1c-84f5-c0a919a0c39e)
