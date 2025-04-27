# Asha AI Chatbot
A chatbot built for enhancing user engagement on the JobsForHer Foundation platform.

## Description
Asha AI Chatbot is a virtual assistant designed to empower women in their careers. It integrates with the JobsForHer platform to provide real-time job listings, mentorship opportunities, event details, and career resources. Built with inclusivity and privacy in mind, Asha provides context-aware interactions that align with women’s career engagement and professional growth. 

### Key Features:
- **Multi-turn Conversations with Memory Handling**: The chatbot remembers previous conversations to ensure natural, ongoing interactions using LangChain’s `ConversationBufferMemory`.
- **Fallback to Human Support**: If the AI cannot answer a question, users can click on a “Contact Support” link to get assistance from a real person.
- **User Activity Tracking**: The chatbot tracks user activity, such as the number of interactions, popular topics, and feedback trends using tools like **Streamlit Analytics** and **Google Analytics**.
- **Real-Time Knowledge Base**: Asha fetches real-time job listings, mentorship opportunities, event updates, and more through APIs.
- **Ethical AI Implementation**: The chatbot is built with a focus on mitigating gender biases and ensuring ethical and responsible AI responses.
- **Inclusivity and Accessibility**: Asha delivers personalized and context-aware responses to meet diverse user needs.

## Technologies Used
The project is built using several powerful technologies to ensure a seamless experience:

- **Python**: Backend logic and AI functionalities.
- **Flask**: Web framework for creating the chatbot API.
- **LangChain**: Used for conversation memory management to handle multi-turn conversations.
- **Streamlit**: Used for tracking user activity and generating analytics.
- **Google Analytics**: For monitoring user engagement and tracking user interactions.
- **APIs**: Integration with external sources for job listings, mentorship programs, and events.
- **HTML/CSS/JS**: Frontend interface for user interactions.
- **NLP & Machine Learning Models**: For understanding and processing user inputs in natural language.

## Installation Instructions

Follow the steps below to get this project running locally:

1. **Clone the Repository**:
   First, clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/asha-ai-chatbot.git
   cd asha-ai-chatbot
