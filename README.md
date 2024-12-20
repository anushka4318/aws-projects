# aws-projects
simple aws project where i make a chatbot using amazon aws lex and amazon aws lambda.
AWS Lex Bot Project Documentation
This documentation provides an overview of the process for creating and testing an AWS Lex Bot. Below are the steps, along with screenshots to help you follow along.

Step 1: Add Language to the Bot
Description:
In this step, you configure the language settings for your AWS Lex bot.

Language Selected: English (US)
Voice Interaction: A text-to-speech voice named "Kimberly" is selected for user interaction.
Intent Classification Confidence Score Threshold: Set to 0.40 to ensure the bot responds confidently based on input interpretation.
Step 2: Initial Bot Testing - Basic Responses
Description:
The first test of the bot ensures it responds correctly to simple user inputs:

Input: "hi"
Response: "Hi, how can I help you today?"
Unrecognized Input: For phrases like "heyo" or "helpp," the bot either falls back to default intent or reverts to its default greeting.
Step 3: Handling Specific Inputs and Context
Description:
Further testing focuses on handling specific inputs and providing clearer feedback:

Input: "junk food"
Response: The bot intelligently requests clarification, offering suggestions for services it can handle (e.g., account balance or payments).
Input: "whatsupp"
Response: The bot processes the input and maintains a clear and helpful tone.
