# Hotel Review Data Analysis and Chatbot Interface

## Project Overview
This project aims to analyze hotel reviews, extract useful insights, and build a chatbot interface to respond to user queries based on these reviews. The key components of this project include data processing, sentiment analysis, and integrating OpenAI's GPT for generating relevant answers to user queries about hotels.

## Installation Instructions

### Clone the repository:
```bash
git clone https://github.com/your-username/your-project-repo.git
cd your-project-repo

Install required libraries:
It is recommended to use a virtual environment. You can create one using:

python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install dependencies:

pip install -r requirements.txt


Interacting with the chatbot:
The chatbot is designed to answer user queries based on hotel reviews. After running the script, you can start interacting with the chatbot by entering queries related to hotel services, ratings, and locations.

Example:


Work Done
Data Processing
We gathered hotel reviews data, which included positive and negative comments from various customers. The reviews were cleaned, and relevant details were extracted, including ratings, popular comments, and hotel location information. We built a system to filter and retrieve relevant hotels based on the user's query.

Chatbot Development
We integrated a chatbot using OpenAI's GPT model, which uses the processed hotel review data to answer user queries. The chatbot is trained to respond intelligently based on the extracted information, including filtering results based on location, rating, and comments.

Results
The final results include:

A functional chatbot that answers queries about hotels based on extracted review data.
Cleaned and structured hotel review data that can be further used for sentiment analysis or other forms of data-driven decision-making.
Positive user feedback regarding the chatbot's accuracy in retrieving relevant hotel information based on user requests.