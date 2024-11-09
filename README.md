✨ Abracadabra ✨
An LLM that Creates Magical Playlists with Llama 2, RAG, Chroma DB, and NeMo Curator
Abracadabra is a custom language model (LLM) powered by Llama 2, designed to create personalized playlists based on user context and emotions. It utilizes a Retrieval-Augmented-Generation (RAG) system with LlamaIndex, Chroma DB, and NVIDIA’s NeMo Curator to handle data cleaning and processing.

🎩 How It Works
Data Curation with NeMo Curator 🎶
First, we process and normalize over half a million songs using NeMo Curator. This involves cleaning artist and song title data for consistency and search precision.

Embedding Generation and Dataset Creation 🧠
Avoiding the need for OpenAI’s API, we generate embeddings directly within our dataset. This enables fast, local access to information without external dependencies.

Indexing with LlamaIndex 📚
With generated embeddings, we index the dataset using LlamaIndex, facilitating efficient semantic search and retrieval.

Database in Chroma DB ⚡️
To optimize the speed and efficiency of playlist generation, we store the dataset in Chroma DB. This significantly reduces model response times, enabling a smooth user interaction.

📊 Dataset Features
Each song in our dataset includes over 14 unique attributes, such as genre, tempo, key, sentiment, and additional musical and contextual details. This diversity allows the model to craft playlists precisely tailored to the user’s mood and context.

🚀 Implementation
To make interaction easy, Abracadabra is implemented on Google Colab, using Gradio as the user interface. This setup allows for:

Creating playlists based on emotions (e.g., sadness, joy, nostalgia)
Generating playlists for specific contexts (e.g., “study music,” “workout music”)
Try it out directly here: Abracadabra Notebook on Colab

⚙️ Requirements
Chroma DB Database
To run this project, download the Chroma DB database here.

Hugging Face Authorization Token
A Hugging Face token with authorization is required to use Llama 2. You can obtain one by creating an account and requesting access through Hugging Face.

Libraries and Dependencies
Ensure that all required dependencies are installed in the Google Colab notebook, included in the repository.

🎉 Try Abracadabra!
Open the notebook on Google Colab, load the database, and start creating magical playlists tailored to your mood or any context you choose. 🪄

📝 Additional Notes
Abracadabra is ideal for exploring the intersection of AI and music, providing a personalized musical experience without relying on external APIs. Leveraging RAG, Chroma DB, and thorough data cleaning with NeMo Curator, responses are both fast and attuned to each user’s unique taste.

