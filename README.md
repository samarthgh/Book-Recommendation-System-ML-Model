# Bookmore - Book Recommendation Website

Bookmore is a book recommendation website that utilizes the power of Python's NumPy library. It showcases the top 50 books on the homepage based on a book database and provides personalized book recommendations to users.

## Technologies Used

- Python
- Flask (Web framework)
- NumPy (Numerical computing library)
- HTML
- CSS
- Bootstrap

## Prerequisites

- Python 3.x
- Flask library
- NumPy library

## Installation

1. Clone the repository to your local machine:

   ```
   git clone <repository-url>
   ```

2. Install the required Python packages using pip:

   ```
   pip install flask numpy
   ```

## Usage

1. Run the Flask server by executing the `app.py` file:

   ```
   python app.py
   ```

   The server will start running on `http://localhost:5000`.

2. Open a web browser and navigate to `http://localhost:5000`.

3. On the homepage, you will find the top 50 books displayed.
<img width="1440" alt="Screenshot 2023-07-10 at 2 12 46 PM" src="https://github.com/samarthgh/Book-Recommendation-System-ML-Model/assets/94733648/9a326ffd-a22b-41ec-aa40-06212f999b33">

4. Click on the "Recommend" tab in the navigation bar to access the book recommendation feature.
<img width="1440" alt="Screenshot 2023-07-10 at 2 13 14 PM" src="https://github.com/samarthgh/Book-Recommendation-System-ML-Model/assets/94733648/2f2ca9ac-ba45-4436-85d1-c3f10ef2ec43">

5. Enter your preferences or any book details in the input field and click "Submit".

6. Bookmore will process your input and recommend books based on your preferences using a recommendation algorithm.

<img width="1440" alt="Screenshot 2023-07-10 at 2 13 32 PM" src="https://github.com/samarthgh/Book-Recommendation-System-ML-Model/assets/94733648/a992cf07-c48f-4cc7-af99-66655ba10150">

7. The recommended books will be displayed on the recommendation page.

8. Click on the "Contact" tab in the navigation bar to access the contact page for any inquiries or feedback.
<img width="1440" alt="Screenshot 2023-07-10 at 2 14 00 PM" src="https://github.com/samarthgh/Book-Recommendation-System-ML-Model/assets/94733648/a349dd58-d49f-48b9-9038-bef49397663c">

9. Explore Bookmore and discover exciting book recommendations tailored to your interests.

## Files

- `app.py`: This file contains the Flask server implementation. It handles the routes for different pages and interacts with the book recommendation functionality.

- `index.html`: This HTML file defines the structure and layout of the homepage. It displays the top 50 books retrieved from the book database.

- `recommend.html`: This HTML file defines the structure and layout of the recommendation page. It provides an input field for users to enter their preferences and displays the recommended books.

- `contact.html`: This HTML file defines the structure and layout of the contact page. It allows users to submit inquiries or feedback.

## Data

- `popular.pkl`: A pickled file containing the data for the top 50 books displayed on the homepage.

- `pt.pkl`: A pickled file containing the book index data.

- `books.pkl`: A pickled file containing book details and attributes.

- `similarity_scores.pkl`: A pickled file containing the similarity scores for book recommendations.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
