[PPT and Implementation.pdf](https://github.com/yansh985/Course-Recommendation-Tool/files/15261103/PPT.and.Implementation.pdf)# Course Tweaker - Automated Course Recommendation System using Udmey Dataset
Course Tweaker is an automated course recommendation system designed to help users discover relevant courses based on their preferences and feedback. This system utilizes machine learning techniques, natural language processing (NLP), and interactive dashboards to provide personalized course suggestions. Using the "neattext" library which is used in Natural Language processing helps in removing stop words, and special characters, and also helps in stemming, lemmatization, and many more in NLP.

# Features
- Homepage & Dashboard: Users are greeted with an intuitive dashboard upon login, featuring interactive charts and elements powered by Chart.js.
- Course Recommendation Engine: Leveraging a dataset from Udemy, the recommendation engine employs custom algorithms such as Cosine Similarity and Linear Similarity to suggest courses tailored to each user's interests.
- Chatbot Integration: A machine learning-driven chatbot, integrated with Flask framework and various libraries, assists users in exploring course options and provides assistance based on natural language inputs. Training and testing are facilitated in Jupyter Notebook for efficient dataset refinement and model development.  
- Filtering and Feedback Loop: User preferences and feedback are continuously collected and processed to enhance the recommendation system's accuracy through a feedback loop mechanism.  
- Final Confirmation and Multiple Course References: Upon receiving course recommendations, users are presented with multiple options and detailed course information for informed decision-making.
- [Flowchart](https://github.com/yansh985/Course-Recommendation-Tool/assets/140264480/4b99c293-7722
- [PPT and Implementation.pdf](https://github.com/yansh985/Course-Recommendation-Tool/files/15261108/PPT.and.Implementation.pdf)

# Workflow
1) Importing the dataset.
2) Performed Text Processing and EDA and generated insights, then converted text to numeric values.
3) After converting text to numeric values, will calculate the cosine similarity score.
4) Then will sort the values that will have similar similarity scores and recommend the course.
5) Integrate the Recommendation System with FLASK Framework.

# Technological Stack
- Frontend: HTML, CSS, JavaScript for user interface development.
- Backend: Flask for server-side development.  
- Machine Learning and NLP: Jupyter notebooks, scikit-learn, "neattext" library for data preprocessing and model training.
- Recommendation Engine: Custom algorithms utilizing Cosine Similarity, Linear Similarity for course recommendation.
- Chatbot: NLP-based chatbot integrated with Flask for natural language interactions.
- Dashboard: Chart.js for dynamic and visually appealing data visualization.

# Getting Started/ Clone this repository in your local system
To get started with Course Tweaker, follow these steps:
1. Clone this repository to your local machine.
2. Install the necessary dependencies listed in requirements.txt. Use pip install -r requirements.txt.
3. Open your terminal/command prompt from your project directory and run the main.py file by executing the command python main.py.
4. Go to your browser and type http://127.0.0.1:5000/ in the address bar.
5. Hurray, that's it!

# If you like this mini project, star this repository.

------
# Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please feel free to open an issue or submit a pull request.


------
# References
https://github.com/pratik9409/Course_recommendation
