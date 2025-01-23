# Readr

Quick book recommendation system based on data from GoodReads reviews.

### Problem Definition
The overwhelming number of books available today makes it difficult for readers to discover books tailored to their preferences. Existing recommendation platforms often require user log-ins or lengthy processes to generate results, which can deter casual users looking for quick suggestions.

### Proposed Solution / Features
* No log-in required for ease of use.
* Quick-stop experience with a short, engaging quiz.
* A recommender system that tailors results to user preferences.
* Provides 5 personalized book recommendations, each including:
  - Book cover
  - Description
  - Author
  - GoodReads rating

### Technology Stack
* **Programming Language:** Python
* **Frameworks:** Flask or Django for the backend, React or Vue.js for the frontend
* **Web Scraping:** BeautifulSoup or Scrapy to extract data from GoodReads
* **Database:** SQLite or PostgreSQL to store quiz responses and scraped data
* **Machine Learning:** Scikit-learn or TensorFlow for implementing the recommendation engine
* **Deployment:** AWS, Heroku, or Vercel for hosting the app

### Workflow
1. **User Interaction:**
   - Users answer a 10-question quiz with 4-6 options per question.
2. **Data Collection:**
   - Web-scraped data from GoodReads provides book metadata.
3. **Recommendation Engine:**
   - Processes quiz responses to generate tailored book suggestions using collaborative or content-based filtering.
4. **Output Display:**
   - Presents book covers, descriptions, authors, and ratings on the final recommendation screen.

### Future Enhancements
* Add user accounts to track reading history and preferences.
* Allow users to leave reviews or ratings directly on Readr.
* Integrate with library or bookstore APIs for real-time availability and purchasing options.
* Expand quiz categories to include more personalized inputs like mood or time commitment.
* Optimize the recommendation algorithm using user feedback.

### Challenges
* Ensuring the accuracy of scraped data and maintaining compliance with GoodReads' terms of service.
* Developing an intuitive, engaging quiz while keeping it concise.
* Balancing performance and personalization in the recommendation engine.
* Scaling the app to handle a large number of users.


## System Design
### User Interface
### System Diagram
### UML Diagram
### ER Diagram
### Success Criteria


