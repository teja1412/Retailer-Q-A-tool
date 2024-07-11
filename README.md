This is an end to end LLM project based on Google Palm and Langchain. We are building a system that can talk to MySQL database. User asks questions in a natural language and the system generates answers by converting those questions to an SQL query and then executing that query on MySQL database. AtliQ Tees is a T-shirt store where they maintain their inventory, sales and discounts data in MySQL database. A store manager will may ask questions such as,

How many white color Adidas t shirts do we have left in the stock?
How much sales our store will generate if we can sell all extra-small size t shirts after applying discounts? The system is intelligent enough to generate accurate queries for given question and execute them on MySQL database

Project Highlights
------------------

AtliQ Tees is a t shirt store that sells Adidas, Nike, Van Heusen and Levi's t shirts
Their inventory, sales and discounts data is stored in a MySQL database
We will build an LLM based question and answer system that will use following,
1) Google Palm LLM
2) Hugging face embeddings
3) Streamlit for UI
4) Langchain framework
5) Chromadb as a vector store
6) Few shot learning
In the UI, store manager will ask questions in a natural language and it will produce the answers

Sample Questions
----------------
1) How many total t shirts are left in total in stock?
2) How many t-shirts do we have left for Nike in XS size and white color?
3) How much is the total price of the inventory for all S-size t-shirts?
4) How much sales amount will be generated if we sell all small size adidas shirts today after discounts?

Project Structure
--------
1) main.py: The main Streamlit application script.
2) langchain_helper.py: This has all the langchain code
3) requirements.txt: A list of required Python packages for the project.
4) few_shots.py: Contains few shot prompts
5) .env: Configuration file for storing your Google API key.
