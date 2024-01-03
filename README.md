The Resume Matching Tool combines LangChain's SentenceTransformers and OpenAI to streamline resume screening. Recruiters input the job description, specify the number of ideal resumes, and upload candidates' resumes.

**Key Features:**

Effortless Screening: Quickly analyze resumes for relevance.
Smart Algorithm: Assigns similarity scores for each candidate.
Concise Summaries: Summarizes key details for efficient review.

**Technology Stack:**

LangChain's SentenceTransformers
SentenceTransformerEmbeddings
OpenAI
Pinecone
Streamlit
Langchain's load_summarize_chain

**How to Use:**

Clone the repo, follow README instructions.

Go to app.pinecone.io, create a new project and then a new index, generate a new API key.

Replace your API key,index name and environment name with the ones in **app.py** file.

generate **OPENAI_API_KEY** and write it in the **.env** file

simple run the app using **streamlit run app.py**

Input job description, set ideal resumes, upload resumes.

Review top matches with scores and concise summaries.

**Benefits:**

Privacy: Operates locally.
Time-Saver: Speeds up the screening process.
