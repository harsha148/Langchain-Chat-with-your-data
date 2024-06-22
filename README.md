# Langchain-Chat-with-your-data
A chatbot powered by OpenAI LLM, that uses Retrieval Augmented Generation (RAG) to retrieve information that is relevant to the query and augment the response using this retrieved data.

We can upload data in the format of a PDF or a webpage link. The uploaded data is converted to embeddings using the OpenAI embeddings model.
Then, we utilize langchain vectorstores to store the generated embeddings into a vector database Chroma DB.

Then, we test different types of retriever techniques to retrieve the information relevant to the query.

Finally, we use Langchain chains and memory to create a chatbot that capable of storing the chat history and also augment its response based on the prior data uploaded.

Happy coding!
