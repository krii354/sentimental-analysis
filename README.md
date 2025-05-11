# Sentiment Analysis GUI Application

This project is a simple sentiment analysis tool with a graphical user interface (GUI) built using Python. It allows users to input a review, determines the sentiment (positive or negative), and provides suggestions to improve the feedback quality.

## Features

* **Input Dialog Box:** Users can input their textual review using a dialog box.
* **Sentiment Detection:** Analyzes the input text and classifies it as Positive or Negative along with confidence score.
* **Constructive Suggestion:** For negative feedback, a suggestion dialog box is shown with a more constructive way to phrase the review.
* **User-Friendly Interface:** Built using Tkinter for simple and intuitive interactions.

## Screenshots

* **Review Input:**
  ![Image](https://github.com/user-attachments/assets/b7f685ca-c9fe-4fa8-8f62-2b7d77514232)
* **Sentiment Result:**
 ![Image](https://github.com/user-attachments/assets/dcd56a87-c26c-43f1-8aad-6733e86c07fc)
* **Suggestion Output:**
  ![Image](https://github.com/user-attachments/assets/d91cdc77-3fb1-4889-9aee-ed40717cbf23)

## Requirements

* Python 3.x
* Libraries:

  * `sklearn`
  * `tkinter`
  * `joblib`
  * `nltk`

## How to Run

1. Clone the repository or download the files.
2. Ensure all required libraries are installed.
3. Run the Jupyter Notebook: `sentimental_analysis.ipynb`
4. Enter a review in the input dialog box and observe the results.

## Example Workflow

1. User inputs: `I don't want to buy it again!!`
2. System classifies: Negative (e.g., 67.59% confidence)
3. Suggestion shown: *"Your feedback is valuable! Constructive suggestions can help improve the experience."*

## License

This project is for educational purposes.

---

Feel free to modify and expand the project according to your needs.
