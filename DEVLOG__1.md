# 🧠 Summer of Making – Devlog by Tanishga Ravikumar Priya
 
Welcome to my devlog! This document tracks my progress building my **mental_health_bot** 🤖💙.



# 📅 Devlog #1 – Project Kickoff

**Date:** July 31, 2025  
**Project Name:** mental_health_bot 

# 🧠 What I’m building
A simple, conversational Python bot that checks in with your mood and gives positive, mood-specific responses. It's like a virtual friend to support your emotional well-being!

# ✅ What I did today
- Created a basic chatbot using Python
- Added a dictionary to store mood-based responses
- Used a loop to keep the conversation going until the user types `'quit'`

# 💻 Code Snippet
```python
def get_response(mood):
    responses = {
        "happy": "That's awesome! Keep smiling 😊",
        "sad": "Always remember, I'm here for you 💙",
        # more...
    }
# Sample Output
How are you feeling today? happy
That's awesome!If you're happy, then I am happy too. Keep smiling 😊
