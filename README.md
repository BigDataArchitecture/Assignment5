# Assignment5

Update our SEVIR application so an authenticated user can only use unto <n> requests to the API. A LIVE admin dashboard that reveals the user analytics and how many queries each user has invoked. Usage logs by user using BigQuery and Google Data Studio. 
  
Two APIs, for Named Entity Recognition and Summarization which are built using Hugging face, Lambda functions and Docker. Updating our streamlit application to display the NER and summarization outputs. 

Name Entity Recognition NLP API: https://0rwjoafjn8.execute-api.us-east-1.amazonaws.com/dev/qa
  
Sample: {"context":"Hi My name is Riya and i stay in New york"}

Output: "answer": "[{'entity': 'B-PER', 'score': 0.95498997, 'index': 5, 'word': 'R', 'start': 14, 'end': 15}, {'entity': 'B-PER', 'score': 0.40459135, 'index': 6, 'word': '##iya', 'start': 15, 'end': 18}, {'entity': 'B-LOC', 'score': 0.73876435, 'index': 11, 'word': 'New', 'start': 33, 'end': 36}, {'entity': 'I-LOC', 'score': 0.7159286, 'index': 12, 'word': 'yo', 'start': 37, 'end': 39}]"
  
Summarization NLP API: https://yto0kae7xb.execute-api.us-east-1.amazonaws.com/dev/qa
  
Sample: {"context":"Another Boston April cold front brought a round of scattered to numerous showers and thunderstorms on Saturday April 21 Some storms became severe and produced mainly large hail."}

Output: "answer": "<pad> another Boston April cold front brought a round of scattered"
  
Streamlit Application: https://share.streamlit.io/shahparth0007/maritime_streamlit/main/streamlit.py
  
Use any of the following Usernames and password: 
1) Parth, Password parth
2) Sreepad, Password Sreepad
3) Ankana, Password Ankana
  
User Manual for using our application: https://docs.google.com/document/d/10ZVVQwX3u5E_jHfZ6pmfwD1nTQxtvwjWj-J8iUCkZrk/edit?usp=sharing
  
