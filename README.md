# Fish-Alert

FishAlert is a dual-purpose project designed to assist elderly individuals in identifying phone scammers and provide interactive learning experiences for kids. The system employs speech-to-text, phone number analysis, and AI-based scam detection techniques, along with text-to-speech functionality. 

**Features**
1. Speech-to-Text: Converts live phone conversations to text using real-time speech recognition.
2. Phone Number Analysis: Extracts details like timezone, location, and carrier from the caller's phone number to validate the source.
3. AI-Powered Scam Detection: Identifies suspicious phrases often used by scammers and offers AI-generated rebuttals to assess the threat.
4. Text-to-Speech Responses: After identifying potential scams, FishAlert generates a verbal response that the elderly user can use during the call.
5. Website Blocker: Block specific websites and use a password to prevent any changes to locked websites

**How It Works**
Firstly, the phone numebr is scammed using an API to extract details like timezona location and what carrier service the phone number is from. Then, when voice is inputted, the speech recognition engine trancscibes the conversation. The transcripted text is then fed into an LLM which analyzes the conversation for specific phrases or keywords that are often used by scammers, and tells you which phrases those are. Then, the AI has a text to speech engine interact with the scammer, both leading the conversation, and keeping you safe from any scams that clone your real voice
For the website blocker, by inputting the URL and your selected password, the program bans that website on your brower by removing all accessible information, and all buttons from it.


**Installation:**
Clone the Repository:  
`git clone https://github.com/aarnavshah12/Fish-Alert`  
`cd Fish-Alert`
     
Install Dependencies:  
`pip install -r requirements.txt`

Setup API Keys:
1. Google Cloud API
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



