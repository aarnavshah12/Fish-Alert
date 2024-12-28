# Fish-Alert  

FishAlert is a dual-purpose project designed to assist elderly individuals in identifying phone scammers and provide interactive learning experiences for kids. The system employs speech-to-text, phone number analysis, and AI-based scam detection techniques, along with text-to-speech functionality. 

**Demo Video:**
https://youtu.be/VTEEbKnR8jM

**Features:**  
1. Speech-to-Text: Converts live phone conversations to text using real-time speech recognition.
2. Phone Number Analysis: Extracts details like timezone, location, and carrier from the caller's phone number to validate the source.
3. AI-Powered Scam Detection: Identifies suspicious phrases often used by scammers and offers AI-generated rebuttals to assess the threat.
4. Text-to-Speech Responses: After identifying potential scams, FishAlert generates a verbal response that the elderly user can use during the call.
5. Website Blocker: Block specific websites and use a password to prevent any changes to locked websites
6. Cyber Security Education: Educating users about Cyber Security and Scamer Identification.

**How It Works:**  
First, the phone number is analyzed using an API to extract key details, such as the timezone, location, and carrier information. When the voice is detected, a speech recognition engine transcribes the conversation. The transcribed text is then processed by a large language model (LLM), which analyzes the conversation for specific phrases or keywords commonly used by scammers and highlights them for you. To protect you further, an AI-driven text-to-speech engine engages with the scammer, guiding the conversation and keeping you safe from scams that may attempt to clone your voice.

For the website blocker, simply input the URL and your selected password. The program then blocks access to the website on your browser by removing all visible content and disabling all interactive buttons. The website blocker uses a blocked list stored in a JSON file, while the overall design leverages Tailwind CSS for an aesthetic and user-friendly interface.


**Installation:**  
Clone the Repository:  
`git clone https://github.com/aarnavshah12/Fish-Alert`  
`cd Fish-Alert`
     
Install Dependencies:  
`pip install pyttsx3 phonenumbers google-cloud-speech google-generativeai requests threading`

Setup API Keys:
1. Google Gemini API
2. NumVerify

Input your API keys  
`GOOGLE_API_KEY=your_google_api_key`  
`NumVerify=your_numverify_key`  

Run the Application:   
`python app.py`

# Pictures

**Homepage:**
![homepage](https://github.com/user-attachments/assets/dbc6c6cd-5bee-4a48-8d36-1c111f231af0)

**Email & Text Checker**
![text checker](https://github.com/user-attachments/assets/623ee37d-4384-45e6-b06c-c6645721311a)

**Contact**
![contact](https://github.com/user-attachments/assets/291904b8-c3de-4a4f-b500-e1d0eab7508c)



