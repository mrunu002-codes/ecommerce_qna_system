This is an end-to-end LLM project using Google PaLM and LangChain.
We are building a Q&A assistant for an online education platform that offers self-paced and instructor-led courses across various domains like Data Science, Web Development, and Digital Marketing.

Students frequently ask questions related to course access, certification, refunds, technical requirements, and instructor interaction. To streamline support and reduce repetitive queries, this system provides a Streamlit-based user interface where learners can ask questions and get instant, context-aware answers.

The backend uses LangChain with Google PaLM to implement a retrieval-augmented generation (RAG) architecture. The system pulls from a curated set of course-related FAQs stored in a vector database (like FAISS) and generates accurate, conversational responses.

Key Highlights:

-Built using Google PaLM API, LangChain, and Streamlit

-Uses a dataset of frequently asked learner questions

-Supports dynamic, natural language queries

-Designed for scalability and easy integration with other edtech tools