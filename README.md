# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222230165

### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm: 

1.Objective: Guide the chatbot to respond concisely to customer inquiries. Prompt Pattern: Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
2. Contextual Prompting Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction. Prompt Pattern: Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
3. Persona-Based Prompting Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging. Prompt Pattern: Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'" 
4. Few-Shot Prompting Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations. Prompt Pattern: Prompt: "Here are some examples of how to handle technical questions: 'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.' 'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?' Now, respond to: 'My app keeps crashing.'" 
5. Chain of Thought Prompting Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues. Prompt Pattern: Prompt: "When a customer reports their laptop overheating, guide them through the following steps: Ask if they are using the laptop on a soft surface. Suggest moving the laptop to a flat, hard surface for better airflow. Ask if they’ve cleaned the vents recently. Recommend restarting the device to see if the issue persists. Now, solve: 'My laptop fan is making a loud noise.'"
6. Instruction with Constraints Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone). Prompt Pattern: Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'" 
7. Reflective Prompting Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings. Prompt Pattern: Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
   
# Prompts:

# 1. Straightforward Prompts:
These are simple, direct queries that help the chatbot handle common customer requests efficiently.

Scenario: A customer asks for product troubleshooting or order status.

Example Prompts and Responses:

Customer Query 1: "What do I do if my laptop isn’t turning on?"

Chatbot Response:

"First, make sure your laptop is plugged in and the power button is working. If it's still not turning on, try holding the power button for 10 seconds to reset it. Let me know if that works."

Customer Query 2: "Where is my order?"

Chatbot Response:

"Could you please provide your order number so I can check the status for you?"

# 2. Tabular Format Prompting:
This technique is helpful when the chatbot needs to present structured data or comparisons in an easy-to-read format, like troubleshooting steps, order status, or product comparisons.

Scenario: A customer asks about product features or compares multiple models.

Example Prompts and Responses:

Customer Query: "Can you show me a comparison of the two models?"

Chatbot Response:


"Sure, here's a table comparing the two models for you:"

![Screenshot 2025-05-02 083244](https://github.com/user-attachments/assets/cb241d8a-d0de-4f78-90b7-4429fe1a56b5)


Chatbot Response:

"Here's a table with steps to troubleshoot your issue:"
![image](https://github.com/user-attachments/assets/faebe31d-db22-49d3-88fc-8bbe2ec6e6e9)


# 3. Preceding Question Prompting:
This technique involves using context from previous customer queries to ensure that the chatbot gives relevant and continuous support.

Scenario: The chatbot needs to maintain context across different queries or follow-up questions.

Example Prompts and Responses:

Customer Query 1: "I ordered a phone last week. When will it arrive?"

Chatbot Response: "Could you please provide your order number so I can check the status?"

Customer Query 2 (after the order number is provided): "What should I do if the phone has a defect?"

Chatbot Response: "Thank you for your order number. If your phone is defective, you can follow these steps for returns or repairs."

Customer Query 3 (follow-up after troubleshooting step): "It still doesn't work. What should I do next?"

Chatbot Response: "I see that the troubleshooting steps didn’t work. Let me escalate this issue to our support team for further assistance."

# Report:
![image](https://github.com/user-attachments/assets/4ed35413-09ff-4d59-acc8-5624f768f609)

# Result: 
Thus the Prompts were exected succcessfully .

