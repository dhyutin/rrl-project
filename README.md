Hotel Suite Success - Multi-Agent System for Hotel Queries
Overview
This project is a multi-agent system designed to handle hotel-related queries using a combination of web scraping, natural language processing, and API integrations. The system can answer user queries about hotels, such as finding hotels within a specific budget, checking amenities, and providing recommendations based on user preferences. The system uses tools like DuckDuckGo search, Booking.com API, and OpenAI's GPT-4 to process and respond to user queries.

Key Features:
Hotel Information Retrieval: The system can fetch detailed information about hotels, including amenities, pricing, and reviews.

Query Processing: It processes user queries to extract relevant information such as location, budget, and preferences.

Multi-Agent Orchestration: The system uses multiple agents to handle different tasks, such as query construction, web search, and answer generation.

Emergency Handling: The system can prioritize hotels based on proximity in emergency situations.

Results:
The system successfully retrieves hotel information based on user queries and provides accurate responses.

It handles complex queries, such as finding hotels with specific amenities within a budget range.

The system can prioritize hotels based on user needs, such as cleanliness and proximity in emergency situations.

Installation
To set up the project locally, follow these steps:

Prerequisites
Python 3.11 or higher

Git

OpenAI API key

Booking.com API key (optional, for hotel search functionality)

Steps
Clone the repository:

bash
Copy
git clone https://github.com/your-username/hotel-suite-success.git
cd hotel-suite-success
Set up a virtual environment:

bash
Copy
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
Install dependencies:

bash
Copy
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the root directory and add the following:

plaintext
Copy
AZURE_OPENAI_API_KEY=your-azure-openai-api-key
AZURE_OPENAI_ENDPOINT=your-azure-openai-endpoint
LANGSMITH_API_KEY=your-langsmith-api-key
LANGSMITH_ENDPOINT=https://api.smith.langchain.com
LANGSMITH_PROJECT=RRL project
BOOKING_COM_API_KEY=your-booking-com-api-key  # Optional
Run the application:

bash
Copy
python -m notebook
Open the final.ipynb notebook in your browser and run the cells to interact with the system.

Usage
Running the Gradio Interface
The project includes a Gradio interface for easy interaction. To launch the interface, run the following command in the notebook or terminal:

bash
Copy
demo.launch()
Example Queries
You can ask the system questions like:

"Suggest me hotels for a stay of three days for 4 guests between the budget of 
900
a
n
d
900and1200. The hotel has at least 1 swimming pool and 2 rooms."

"Consider you are the manager of Hotel Orrington. Can you accommodate the people traveling in the infinity bus?"

"Clara is extremely meticulous when it comes to cleanliness and expects everything she uses and everywhere she stays to be well-organized and tidy. Clara is in an emergency situation and needs to use the room for medical purposes. Suggest a hotel for Clara."

Results
Example Outputs
Query: "Suggest me hotels for a stay of three days for 4 guests between the budget of 
900
a
n
d
900and1200. The hotel has at least 1 swimming pool and 2 rooms."

Output: "Yes, I found hotels that match your criteria. Here are the details: [Hotel details]."

Query: "Clara is in an emergency situation and needs a clean and organized hotel room for medical purposes."

Output: "Based on Clara's needs, I recommend [Hotel Name] which is known for its cleanliness and is located close to medical facilities."

Query: "Can Hotel Orrington accommodate an infinite number of guests?"

Output: "No, Hotel Orrington cannot accommodate an infinite number of guests due to limited room availability."

Contributors
[Your Name]

[Team Member Names]
