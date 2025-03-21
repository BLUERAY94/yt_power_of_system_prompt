# yt_power_of_system_prompt
Showcasing the Usage of Prompt componenents like System msg, Human msg &amp; AI msg

Prompt Template consists of 3 components:

1) < SYSTEM > 	-----------> Impacts the behaviour of the AI
   
3) < USER > 	--------------> AI responds to this message
   
5) < AI RESPONSE > -----> Actual AI Response


Summary:

* AI does not violate the System Prompt most of the times. 

* So Developer should insert the instructions to AI in SYSTEM msg section.

* NOTE: Always insert the User query into Human msg section only.


How to run this script:

Step 1) Git clone or download this repository in your local

Step 2) Create Virtual Environment in Python

Step 3) Go to Groq website and generate ACCESS_KEY to use the LLM models

Step 4) Create .env file and update your GROQ KEY into 'Grok_key' variable

Step 5) In Human_msg variable, you can feed various 'user_resume' as input. So edit this 'user_resume' string as per your input need.

Step 6) Run main.py
