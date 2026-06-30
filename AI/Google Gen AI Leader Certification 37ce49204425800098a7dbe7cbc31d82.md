# Google Gen AI Leader Certification

[Study Guide](https://services.google.com/fh/files/misc/generative_ai_leader_exam_guide_english.pdf)

**AI is a computer system**, that can perform tasks that otherwise require human intelligence. (simulate)

- problem solving
- decision making
- understanding a language
- recognising speech and images
    
    
    Simulate - mimic aspects
    
    emulate - replicate exact process
    

ML - Machines that are autonomous, learn and perform task without explicit programming

DL - Machines that are connected through a neural network and can solve complex problems

GenAI - subset of AI, that generates  content eg: Image, Video, Text, Audio (spans all 3 spaces AI to perform tasks, ML to learn, DL to perform complex task like image generation etc)

Gen AI is a subset of AI that focusses on creating new content or data that is novel and realistic. It can analyse data but also generate new data itself.

It involves adv machine learning techniques

- Generative Adversarial network (GAN)
- Variational auto-encoders (VAE)
- transformer models eg GPT

**GENAI has many modalities**

- vision - generate realistic images, videos
- text - generate human like text
- audio -  composing music
- molecular - drug discovery via genomic data.

LLMs’ which generate out human like text is a subset of GenAI but is often conflating with being AI due to it being most popular and developed.

AI basically focusses on analysis and decision making, GenAI focusses on generating content, creating new , original outputs(specific branch of AI used for generative purposes).

NLP is a ML technique that can understand the context of a corpus ( a body of related text)

What does NLP do

- Analyse and interpret text within docs, email messages
- Interpret or contextualise spoken token eg sentiment analysis
- synthesise speech eg voice assistance talking to you
- Automatically translate spoken or written phrases and sentences between languages
- Interpret spoken or written commands and determine appropriate actions

**NLP process**

Text Wrangling → Language understanding (syntax/ structure) → processing and functionality

Conversion               Parts of Speech                                   Named entity recognition

Sanitisation               Chunking                                              N-gram Identification

Tokenisation    →      Dependency parsing            →           Sentiment analysis

Stemming                 Constituency parsing

Lemmatisation 

**Supervised Learning (SL)**

ML task/ function that needs to be provided training data. Training data is when you provide the labelled data and the machine can learn from these results

- classification models
- regression models

UnSupervised Learning

ML task/function that needs no existing data. UL will take unlabelled data and discover its patterns and applying its own labels

- Clustering
- Association
- Dimensionality reduction

What is an ML Model ?

model - informative representation  of an object, person or system.

- concrete - have physical form (eg. design a vehicle, a person posing for a painting)
- abstract - expressed as behavioural patterns (eg. mathematical,  computer code and written words)

ML model - is a function that takes the data, performs an ML algorithm to produce a prediction. ML model is trained. Not to be confused with the training model, which is learning to make correct predictions. A ML model can be training model that is just deployed once all it has been tuned to make good predictions.

training data(labelled data) → Learning algorithms (hyper tuning) → ML model (deployed) (works with unlabelled data)

What is a Feature ?

its a characteristic extracted from our unstructured dataset that has been prepared to be ingested by our ML model to infer a prediction

ML models generally only accept numerical data, so preparing is encoding data into machine readable format

Feature engineering - process of extracting features from our provided data sources.

$$
data source 1, 
data source 2 -> raw data -> feature -> ML model
$$

What is Inference ? Act of requesting and getting a prediction

- input data → ML model → output prediction

What is Foundation model ?

general purpose model that is trained on vast amounts of data. We that FM is retrained because it can be fine tuned for specific tasks

LLMs are specialised subsets of FM that uses transformer architecture

What is a LLM ?

is a FM that implements the transformer architecture

```jsx
NLP -> LLM <feedback <-> prediction> Output
```

**Tokens and  Capacity**

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image.jpeg)

**Memory**

each token is a sequence that requires memory, as the token count increases, memory increases, memory usage eventually becomes exhausted

**Compute**

model perform more operations for each additional token Longer sequences require more compute

AI services that offer Models-as-a-Service will often have  a limit of combined input and output.

**Prompt Tuning**

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%201.jpeg)

**Prompt Chaining**

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%202.jpeg)

**Chain-of-Thought**

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%203.jpeg)

TPU (Tensor Processing Unit)

is an accelerator application-specific integrated circuit(ASIC) developed by Google for neural network machine learning, using Google TensorFlow software

- are designed for a high  volume of low precision computation.

iGPU (integrated graphic processing unit)

is when a CPU contains the capabilities of performing a task similar to dedicated GPUs’

Intel Lunar Lake chip

dGPU - dedicated GPU - graphics card (better)

GPU (General processing unit)

- high resolution images and video concurrently
- can also perform parallel operations on multiple sets of data

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%204.jpeg)

CUDA (Compute unified device architecture)

NVIDIA manufactures GPUs

- is a parallel computing platform and API by NVIDIA for general purpose computing
- EC2 P3 on AWS - 8 NVIDIA Tesla V100 GPUs

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%205.jpeg)

What is Labelling ?

- identify raw data (image, text) and add one or more meaningful and informative labels to provide context so that a machine learning model can learn from.

Fine Tuning llms

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%206.jpeg)

![image.jpeg](Google%20Gen%20AI%20Leader%20Certification/image%207.jpeg)

![image.png](Google%20Gen%20AI%20Leader%20Certification/image.png)

![Screenshot 2026-06-15 at 4.16.51 pm.jpg](Google%20Gen%20AI%20Leader%20Certification/Screenshot_2026-06-15_at_4.16.51_pm.jpg)

**RAG Engine**

is a data framework that allows you to transform your data to and from your VectorDB storage.

V**ertex AI Search**

out-of-the-box RAG system

- Structured Catalog (hotels, directories)
- unstructured (article with metadata)
- connectors (google workspace)
- public sites

Site search with AI mode

- pre-built google search index, adv crawling
- structured catalog
- unstructured

Media search

Search for commerce

**Grounding**

connecting the output of an AI system to something real and verifiable in the world, rather than just generating plausible sounding text

- with google search
- with google maps
- RAG
- elasticsearch

**Google Vertex AI search**

- custom search (datasources like structured catalog, unstructured, connectors and public sites)
- site search with AI mode (data sources are like prebuilt google search index, advanced crawling, structured catalog, unstructured (metadata, articles)
- media search (images, videos and audio files)
- search for commerce (retail search api)

**Model Garden**

is a model catalog showing available models and their model cards that you can use with GCP.

Gemini-vs-Gemma

Gemini - full managed by google, accessible over api, multi modal (image, text, audio)

- grounding, json sturctured output, thinking mode

Gemma

open weights model. run the model on your own compute. Older models can do text to text new models are multi-model. your own integrations needs to be built

**Agent Assist**

Real time on the call AI support for your human support team

- Summarisation
- Knowledge assist
- Smart reply
- Build your own assist

**Conversational Agents**

agents provide proactive, personalised self service and natural, human like voices for highly engaging customer experiences. An agent replaces the role of a customer support human.

- predefined templates easy to start a  conversational agent.

**Notebook LLM** is a research and note-taking LLM - can make flashcards, mind map, podcasts. Upload text, pdf, videos, youtube videos to generate your own notes.

**Gemini for Google Workspace integrated.**

**Google Gemini Gems -** 

- create your own sub agents within gmail like - outreach specialist (craft personalised messages to potential customers, build relationships and drive engagement.

Google Videos - generate video using veo

Vertex AI Studio Chat -make your personal  chat for ex language tutor 

Vertex AI Studio generate image/ Generate video 

Agent garden -  is a curated library with google clouds enterprise agent platform that provides prebuilt agent samples. These samples are designed to help developers quickly jumpstart the creation of AI agents by providing high-quality, functional templates for common AI patterns.

Agent 2 Agent (A2A) - open protocol securely communication from one agent to another, similar to MCP by anthropic. 

MCP - external systems talking to agent

## Helpful Resources

[Google Cloud Skills Boost - Intro to Gen AI](https://www.cloudskillsboost.google/paths/118)