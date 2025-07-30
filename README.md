Agentic AI CV Summarizer
Project Overview:
Developed an intelligent AI-powered system that automates extraction, analysis, and summarization of professional CVs from PDF files, enabling quick generation of concise and structured candidate profiles.

Key Contributions & Technologies:

PDF Text Extraction: Utilized PyMuPDF to reliably extract raw text from diverse CV PDF formats.

Advanced Summarization: Applied Long-T5 transformer model capable of processing long documents for high-quality abstractive summarization.

Structured Information Parsing: Designed algorithms to identify and extract key CV sections such as Skills, Education, Experience, Projects, and professional links (Portfolio, GitHub, LinkedIn).

Memory & Retrieval: Integrated FAISS vector store for embedding CV summaries, enabling efficient similarity search and recall of past summaries, simulating a memory-enabled agent.

Modular Task Planning: Implemented a simple planning mechanism to decompose user commands into subtasks such as extraction, summarization, research, and memory recall.

Model & Embeddings: Leveraged Hugging Face Transformers and Sentence-Transformers for language understanding and semantic vectorization.

Deployment: Developed on Google Colab using free/open-source models and libraries for easy access and demonstration without cost.

User Interaction: Built an interactive command-driven interface for uploading CVs and selecting summary types (concise, structured, LinkedIn style).

Impact:

Streamlined CV analysis and candidate profiling process for recruiters or job seekers.

Demonstrated integration of state-of-the-art NLP techniques with practical applications in HR-tech and personal branding.

Showcased capabilities in combining multiple AI techniques to build semi-agentic systems with memory and planning features.
