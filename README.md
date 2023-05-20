# Course-Cupid-Course-Recommender-System---DDA4210-Advanced-Machine-Learning-Group-Final-Project
CourseCupid: Personalized Course Recommender for CUHKSZ Students

CourseCupid is a course recommender system designed to assist students at the Chinese University of Hong Kong, Shenzhen (CUHKSZ) in selecting suitable courses based on their interests. With a vast selection of over a hundred courses available, it can be challenging for students to find the courses that align with their preferences.

Motivation:
The motivation behind CourseCupid stems from the need for a personalized course recommendation tool at CUHKSZ. Recognizing the absence of such a system, a team of students - Edward Jayadi Halim, Richard Cornelius Suwandi, Tan Felicia Adriyanti Jonathan, and Calvin Kristianto Thayono - embarked on developing CourseCupid to address this demand.

Solution:
The solution involves several key components:

1. Data Collection: The team collected data from the university course catalog, available through the Student Information System (SIS) website. They gathered information on 125 different General Education (GE) courses, including course codes, titles, and descriptions.

2. Preprocessing: The collected data underwent preprocessing steps, including converting text to lowercase, replacing newline and tab characters with spaces, removing stopwords, non-English characters, punctuation, and double quotation marks, and stripping leading and trailing whitespaces.

3. Modeling: A pipeline was created to convert the user's query into a vector representation and calculate cosine similarity between the query and feature vectors of each course. Feature vectors were obtained using Spacy's pre-trained English language model.

4. Deployment: The CourseCupid application was deployed, allowing students to access the course recommendation system through a user-friendly web interface.

Deployment Link: [CourseCupid](https://coursecupid.streamlit.app)

Suggestions for Future Work:
- Collect external data from users through questionnaires to improve the recommendation system.
- Incorporate additional features into the model to enhance the accuracy of course suggestions.
- Implement a hybrid or more advanced recommendation model to further refine the recommendations.
- Extend CourseCupid to recommend courses beyond General Education (GE) courses.

Feel free to explore the CourseCupid application and provide feedback for further improvements.

References:
- Spacy pipeline: [https://spacy.io/models](https://spacy.io/models)
- Recommender Systems: It's Not All About the Accuracy: [https://gab41.lab41.org/recommender-systems-its-not-all-about-the-accuracy-562c7dceeaff](https://gab41.lab41.org/recommender-systems-its-not-all-about-the-accuracy-562c7dceeaff)
- Natural Language Processing with Spacy in Python: [https://realpython.com/natural-language-processing-spacy-python/](https://realpython.com/natural-language-processing-spacy-python/)
- PySpellChecker: [https://pypi.org/project/pyspellchecker/](https://pypi.org/project/pyspellchecker/)
- How to Write a Spelling Corrector by Peter Norvig: [https://norvig.com/spell-correct.html](https://norvig.com/spell-correct.html)

