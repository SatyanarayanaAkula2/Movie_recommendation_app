AI-POWERED MOVIE RECOMMENDATION SYSTEM

An intelligent movie recommendation system that provides personalized movie suggestions based on user preferences such as genre, recency, and similar titles. The system uses LLM-based processing to generate relevant recommendations in real time through an interactive interface.

FEATURES

- Provides personalized movie recommendations based on multiple user preferences
- Supports inputs such as genre, recent/latest movies, and similar titles
- Generates real-time recommendations using Gemini API
- Uses LangChain to structure and manage the recommendation pipeline
- Interactive and user-friendly interface built with Streamlit

TECH STACK

- Python
- Streamlit (Frontend UI)
- LangChain (LLM orchestration)
- Google Gemini API (AI model)

HOW IT WORKS

1. User enters preferences (e.g., "recent action movies" or "movies like Inception")
2. Input is processed and structured using LangChain
3. Gemini API interprets the query and generates recommendations
4. Results are formatted and filtered
5. Top movie recommendations are displayed on the UI

INSTALLATION

1. Clone the repository
   git clone https://github.com/SatyanarayanaAkula/Movie_recommendation_app.git

2. Navigate to the project folder
   cd Movie_recommendation

3. Install dependencies
   pip install -r requirements.txt

4. Run the application
   streamlit run Movie_Recommendation.py

ENVIRONMENT VARIABLES
Create a .env file and add your API key:
GEMINI_API_KEY=your_api_key_here

FUTURE IMPROVEMENTS

- Add user history-based recommendations
- Integrate external datasets like TMDB or IMDb
- Improve filtering (ratings, language, year)
- Deploy as a scalable web application

⭐If you Like this project,give it a star on Github!
