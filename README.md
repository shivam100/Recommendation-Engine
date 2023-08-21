# Recommendation-Engine
Content Based Recommendation Engine Using GPT3 using Retrieval Augmented Generation(RAG) method. 

Used OPEN AI's Da-vinci model to create embeddings for the texts (Courses, Modeules and their description). 
Stored the embeddings in PineCone Vector

Created specific prompt instructions on how to handle completion request. 
Leveraged text-davinci-003 to create completion and controlled the completions as per the context (queried the question in the pinecone's vector space) to generate repopnse as per the content. 
