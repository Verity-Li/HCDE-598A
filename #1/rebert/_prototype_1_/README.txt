The excercise I tried: 
Chapter 1 - starting the chat, Exploration 1.1 + 1.2 + 1.3

MODIFICATION:
recommender_1.1.py
- line 37 #changed the model to a cheaper Openai model
- line 46 #replaced with my own API key. I know I should not directly put API key in the code, but as this is a homework, I just put it this way!

[Explore 1.1]
- line 58 #modified [MOVIE_RECOMMENDER_PERSONA_PROMPT] by adding 'Your recommendation should only focused on documentary.' in the prompt

[Explore 1.2]
- line 121,123 #get [total_token] from the response and return it
- line 132 #initializing [total_chat_token_usage] as 0
- line 142 #get the value of [chat_context] & [chat_token_usage] from [make_chat_request]
- line 151-155 #print single-time token usage & total token usage

[Explore 1.3]
- line 39-41 #include two new constants: OAI_MODEL_TEMPERATURE and OAI_MODEL_MAX_TOKENS.
- line 78,79 #defined the value of [temperature] & [max_tokens] for the generated content

HOW TO USE:
- put your API key into line 46
- run the recommender_1.1.py file

