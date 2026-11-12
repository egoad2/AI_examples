.
Notebook 1:

AI_301_Log_Classifier.ipynb

Dataset:

Plain Text
Cisco Syslog
Linux Auth Logs
Windows Security Logs

Categories:

Plain Text
Authentication
Routing
Switching
Interface
Security
Service
Configuration

Students train:

Python
CountVectorizer
+
LogisticRegression

The model will train in under a second.

Prediction is nearly instantaneous.

They can directly compare:

Model	Response Time
Logistic Regression	< 1 ms
DistilBERT	~100-500 ms
Qwen 7B	Several seconds

That drives home the "use the right tool" lesson.

Notebook 2:

AI_302_Malicious_Log_Detection.ipynb

Use a subset of Boss of the SOC or Cowrie logs.

Binary classifier:

Plain Text
Benign
Malicious

Students learn:

Precision
Recall
False Positives
False Negatives

which maps directly to SOC work.