# Fake_News_Detection
The purpose of this website is to display the results of tweets that were run through a machine learning BERT model that labeled each tweet as true or false. The tweets are seperated by if they are coming from verified accounts or unverified accounts. 
The load_pretrained model contains the BERT ML model that was used for this analysis. 
I have created a web application using Flask that allows a user to input text (preferably covid-related) that they wish to detect as real or fake, hit submit, and be shown whether the machine learning model detected it as real or fake. The machine learning model for the web application uses a passive-aggressive classifier and TFID Vectorizer. The model has a 90% training accuracy and is trained on a collection of covid-19 related tweets. I am in the process of improving its reliability, accuracy, and versatility. I also hope to deploy it once I improve the model. For now, it runs locally. 
The files needed to run the program are: Constraint_Train_p.csv (which is the data that the model is trained on), main.py, model.pkl, index.html, and  style.css.
Attached is the layout of how the files should be organized, as well as how the website looks. Original code attributed by https://github.com/Spidy20/Fake_News_Detection.git - however I had to make many changes in order to achieve specific outcomes and used an entirely different ML model.

This was presented at my college's research symposium, where an article came about it: https://news.njit.edu/computing-senior-makes-fake-tweets-detector-satire-checker-next


<img width="688" alt="image" src="https://user-images.githubusercontent.com/92758174/179439139-3a530c99-622b-4f27-9cc7-7b2f6dad71d6.png">
<img width="580" alt="image (1)" src="https://user-images.githubusercontent.com/92758174/179439146-bb78b212-a6e5-4709-a557-a85aa1316795.png">
