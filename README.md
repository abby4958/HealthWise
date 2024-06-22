# MedMind: Intelligent Chatbot for Medical Literature Insights
**Overview:**
Developed a cutting-edge chatbot that enables users to interact with medical literature in a conversational manner, leveraging the power of Retrieval Augmented Generation (RAG) to provide accurate and relevant responses.

**Technologies:**
The project utilizes BioMistal 7B LLM, a specialized fine-tuned language model trained on PubMed datasets, to generate high-quality responses. PubMedBert is used as an embedding layer, taking advantage of its medical domain expertise. Qdrant, an open-source vector database, stores converted vector embeddings from uploaded documents, enabling efficient retrieval and generation of relevant information. The Langchain and Llama.cpp orchestration framework facilitates seamless integration of these components.

**Outcome:**
This innovative chatbot allows users to upload medical-related PDF documents and ask questions about the content, receiving accurate and informative responses. By harnessing the power of RAG and specialized medical AI models, MedMind bridges the gap between medical literature and conversational interfaces, making it easier for healthcare professionals and researchers to access and engage with relevant information.
