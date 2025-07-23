Buddy Chatbot - A Rule-Based Chatbot with GUI
https://demo-screenshot.png <!-- Add a screenshot if available -->

A friendly rule-based chatbot with a graphical user interface built using Python and Tkinter. The chatbot responds to user inputs based on predefined rules with a variety of responses to make conversations more natural.

Features
Interactive GUI: Separate input and output windows for better user experience

Personality Simulation: Random moods and typing speeds for more human-like interaction

Conversation History: Full record of all messages exchanged

Typing Indicators: Visual feedback when the bot is "thinking"

Context-Aware Responses: Handles greetings, time/date queries, and common questions

Multiple Response Variations: Avoids repetitive answers with randomized responses

Timestamps: All messages include time markers

Installation
Clone the repository:

bash
git clone https://github.com/yourusername/buddy-chatbot.git
cd buddy-chatbot
Ensure you have Python 3.x installed

Run the chatbot:

bash
python buddy_chatbot.py
Usage
Type your message in the input window

Press Enter or click "Send Message"

View the conversation in the output window (click "Show Chat Window" if hidden)

The bot will respond based on recognized patterns in your message

Example Interactions:
text
User: Hello
Buddy: Hey there! What's up?

User: What time is it?
Buddy: Right now it's 03:45 PM

User: Thank you
Buddy: Happy to help!
Customization
You can easily modify the bot's behavior by editing these aspects:

Bot Personality:

Change self.mood options in __init__

Adjust self.typing_speed range

Response Patterns:

Add new condition blocks in generate_response()

Expand response lists for existing conditions

Appearance:

Modify colors in the GUI setup

Change fonts in the font configurations

Dependencies
Python 3.x

Tkinter (usually included with Python)

Known Limitations
Only understands exact keyword matches

No conversation memory between sessions

Limited to predefined response patterns

Basic natural language understanding

Future Improvements
Add sentiment analysis for more nuanced responses

Implement conversation memory

Add more response patterns and topics

Include emoji support

Add user preferences/settings

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

New chat
