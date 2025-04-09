# ✨ Abracadabra ✨

![Abracadabra Banner](https://imgur.com/d0uJBFU.png)

### An LLM for Creating Magical Playlists with Llama 2, RAG, Chroma DB, and NeMo Curator

Welcome to **Abracadabra**! This is a custom language model (LLM) powered by **Llama 2** that generates personalized playlists based on user mood, context, and emotional preference. It leverages a **Retrieval-Augmented-Generation (RAG)** architecture with **LlamaIndex**, **Chroma DB**, and **NVIDIA’s NeMo Curator** for data cleaning and processing.

---

## 🎩 How It Works

**Abracadabra** combines multiple advanced AI techniques to provide a seamless playlist creation experience:

1. **Data Curation with NeMo Curator** 🎶  
   Cleaned and normalized a dataset of over half a million songs, ensuring consistency in artist names and song titles.

2. **Embedding Generation and Dataset Creation** 🧠  
   Generated embeddings directly within the dataset to enable local, API-free access to song information.

3. **Indexing with LlamaIndex** 📚  
   Indexed the dataset with LlamaIndex, allowing for efficient and fast semantic search.

4. **Database Optimization with Chroma DB** ⚡️  
   Stored the dataset in **Chroma DB** to further optimize retrieval speed, making playlist generation faster and more responsive.

---

## 📊 Dataset Features

Each song in the **Abracadabra** dataset includes detailed attributes for a highly personalized music recommendation experience:

| Feature                     | Description                                                                                  | Example                               |
|-----------------------------|----------------------------------------------------------------------------------------------|---------------------------------------|
| **Artist(s)**               | Name of the artist(s) performing the song                                                   | King Crimson                          |
| **Song**                    | Title of the song                                                                           | ConstruKction Of Light                |
| **Text**                    | Lyrics or main text of the song                                                             | "Pain, day, sky..."                   |
| **Length**                  | Duration of the song                                                                        | 08:40                                 |
| **Emotion**                 | Main emotion associated with the song                                                       | Sadness                               |
| **Genre**                   | Genres associated with the song                                                             | Rock, Progressive Rock, Jazz          |
| **Album**                   | Album in which the song is featured                                                         | The ConstruKction of Light            |
| **Release Date**            | Release date of the song                                                                    | 18th March 2016                       |
| **Key**                     | Musical key of the song                                                                     | B minor                               |
| **Tempo**                   | Beats per minute (BPM)                                                                      | 160                                   |
| **Loudness (dB)**           | Loudness level in decibels                                                                  | -11.99 dB                             |
| **Time Signature**          | Time signature used in the song                                                             | 5/4                                   |
| **Song Number**             | Track position in the album                                                                 | 2 of 9                                |
| **Explicit**                | Indicates if the song has explicit content                                                  | No                                    |
| **Popularity**              | Popularity score based on metrics                                                           | 23                                    |
| **Energy**                  | Energy level of the song (0-100)                                                            | 63                                    |
| **Danceability**            | Danceability score (0-100)                                                                  | 50                                    |
| **Positiveness**            | Measure of positivity in the song (0-100)                                                   | 50                                    |
| **Speechiness**             | Degree of speech presence in the song (0-100)                                               | 4                                     |
| **Liveness**                | Likelihood the track was performed live (0-100)                                             | 14                                    |
| **Acousticness**            | Measure of acoustic sound presence (0-100)                                                  | 11                                    |
| **Instrumentalness**        | Likelihood of being instrumental (0-100)                                                    | 1                                     |
| **Good for Party**          | Suitability for party playlists (binary)                                                    | 0                                     |
| **Good for Work/Study**     | Suitability for work or study playlists (binary)                                            | 0                                     |
| **Good for Relaxation/Meditation** | Suitability for relaxation or meditation playlists (binary)                      | 0                                     |
| **Good for Exercise**       | Suitability for exercise playlists (binary)                                                 | 0                                     |
| **Good for Running**        | Suitability for running playlists (binary)                                                  | 0                                     |
| **Good for Yoga/Stretching**| Suitability for yoga/stretching playlists (binary)                                          | 0                                     |
| **Good for Driving**        | Suitability for driving playlists (binary)                                                  | 0                                     |
| **Good for Social Gatherings** | Suitability for social gatherings playlists (binary)                                    | 0                                     |
| **Good for Morning Routine**| Suitability for morning routine playlists (binary)                                          | 0                                     |
| **Similar Songs**           | List of similar songs with artist names and similarity scores                               | Similar Artist 1: King Crimson, Similarity Score: 0.9997 |

---

## 🚀 Implementation

**Abracadabra** is implemented on **Google Colab** using **Gradio** as the user interface, making it easy to interact with the model. Key functionalities include:

- **Emotion-Based Playlists**: Create playlists for moods like sadness, joy, nostalgia, and more.
- **Context-Based Playlists**: Generate playlists for specific activities (e.g., “study music,” “workout music”).

### 🔗 [Try it out here on Google Colab](https://colab.research.google.com/drive/12Y_IIBaAtTr7ODtwI75y59ylIRbsaak5?authuser=1)

---

## ⚙️ Requirements

To get started with **Abracadabra**, make sure you have the following:

- **Chroma DB Database**  
  > Download the preprocessed Chroma DB database [here](https://drive.google.com/file/d/1eVXmNEMkGUPeA4sJd1qgsA5VztEVVL7S/view?usp=sharing).

- **Hugging Face Authorization Token**  
  > **Note**: A Hugging Face token with authorization is required to use Llama 2. Obtain one by creating an account on Hugging Face and requesting access.

- **Libraries and Dependencies**  
  > Ensure that all necessary dependencies are installed in the Google Colab notebook, provided in the repository.

---
📂 Dataset
The base dataset used in Abracadabra is now publicly available on Kaggle:
# 🔗 [900K+ Spotify Dataset with Lyrics, Emotions, and Audio Features](https://www.kaggle.com/datasets/devdope/900k-spotify/data)
You can use this dataset for:

Emotion-aware playlist generation

Music recommendation systems

LLM/RAG-based musical applications

NLP and emotion classification research using lyrics

To explore or download the data, visit the Kaggle page linked above.

---
## 🎉 Try Abracadabra!

Open the notebook on Google Colab, load the Chroma DB database, and start creating magical playlists based on your mood or any activity you choose. 🪄

---

### 📝 Additional Notes

Abracadabra offers a unique intersection between AI and music, allowing for a tailored and immersive musical experience without relying on external APIs. Using RAG, Chroma DB, and thorough data curation with NeMo Curator, the model provides fast and personalized responses that adapt to each user's taste.

---

Enjoy your musical journey with **Abracadabra**! 🎶

