This chatbot allows users to upload PDFs and ask math-related questions, generating responses based on the document's content. Built with Streamlit, LangChain, and FAISS, it processes PDFs, extracts relevant text, and retrieves information efficiently. OpenAI’s GPT-4 is used to generate accurate and contextual answers, making it useful for students, researchers, and professionals.

When a PDF is uploaded, the chatbot converts it into searchable chunks and stores them in a vector database using FAISS. When a question is asked, it finds the most relevant text and provides a precise response. Metadata such as page numbers and filenames are considered to improve accuracy.

This project simplifies the process of extracting useful information from large PDFs without manual searching. Future enhancements will include support for more file formats, improved response accuracy, and a refined UI for better user experience.
