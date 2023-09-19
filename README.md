Uber Chatbot: Inclusive Ride-Hailing for All
Streamlining the booking experience for elderly and disabled individuals
Overview
Ride-hailing platforms have transformed urban transportation. Amidst this innovation, our chatbot stands out by focusing on creating an inclusive experience, especially for the elderly and disabled. Using a GPT-2 model fine-tuned for question answering, the chatbot seeks to demystify the booking process on platforms like Uber.

Motivation
The essence of our chatbot is to not just simplify, but to make ride-booking accessible. Recognizing the challenges the elderly and disabled individuals face with tech interfaces, our solution is conversational. This ensures that users, regardless of their tech-savviness, can navigate and avail services without hindrance.

Features
Natural Language Processing: Guiding users through their booking journey using human-like interactions.
Tailored for Uber: Specific to the Uber platform, ensuring relevance.
Inclusivity: Simplifies the process for the elderly and disabled, reducing cognitive load.
Primary Bookings: Facilitating private, child seat, and standard bookings.

gpt2.ipynb: Algorithm, Training, and Fine-Tuning
Inside the gpt2.ipynb notebook, you'll find a comprehensive dive into:

Data Generation Algorithm: This algorithm is responsible for creating a diverse dataset, encapsulating user intents from basic cab availability inquiries to intricate, personalized cab recommendations.

Model Initialization: We initialize the GPT-2 model, setting it up for our specific task.

Training Parameters: Detailed documentation on the parameters chosen for training, offering insight into our optimization choices.

Fine-Tuning Process: Explore the steps we took to fine-tune the GPT-2 model for the specialized task of question answering in the context of ride-hailing.

For a hands-on look and deeper understanding, it's recommended to navigate through the gpt2.ipynb notebook directly.

Dependencies
Make sure to install the following Python libraries before running the code:
!pip install transformers

Primary Libraries:
transformers: For using and fine-tuning the GPT-2 model.

Usage
Clone the repository to your local machine.
Install the required dependencies.
Navigate to the code directory.
Run the gpt2.ipynb notebook to understand the data generation and model fine-tuning process.

Future Scope
The present chatbot serves as a beacon for a more inclusive digital horizon. As technology advances, we envision further refining this tool, spotlighting the transformative power of AI-driven conversational tools in fostering inclusivity.

