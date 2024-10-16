
ADD FOLDER FOR GPT REPO: https://github.com/kalistamp/GPT

# ITS LLMs not LLM


**RED PROMPTS**

https://github.com/declare-lab/red-instruct/tree/main


### General Memory Requirements for LLMs

For many LLMs, a rough estimate is that you need at least 2-3 times the size of the model in RAM to run it effectively. For an 8B model, this could mean needing anywhere from 16 GB to 24 GB of RAM, depending on the specific implementation and workload.

```1 billion parameters ≈ 4-6 GB of storage space```

***
***



ALL LLM Related

* [Repository](https://github.com/kalistamp/llm/blob/main/ai_privacy_guide.md) explains use of AI technologies in a safe and privacy-respecting manner - [Source](https://github.com/iAnonymous3000/ai-privacy-guide?tab=readme-ov-file#self-hosted-ai-solutions)

TEST ALL BELOW:

There are several popular programs for running Large Language Models (LLMs) locally on your hardware besides Ollama. Here's a list of some of the most commonly used options:

1. LlamaGPT (formerly known as GPT4All)
2. oobabooga's Text Generation WebUI
3. llama.cpp
4. LocalAI
5. Kobold AI
6. KoboldCPP
7. LM Studio
8. Transformers.js
9. Llama-X
10. ExLlama
11. Text Generation Inference (TGI)
12. Alpaca.cpp
13. FastChat
14. SimpleAI
15. PrivateGPT

These programs offer various features and capabilities for running LLMs locally. Some are more user-friendly with graphical interfaces, while others are command-line tools that offer more flexibility for advanced users.

***
***

**Specialized Language Models and Their Applications**
=====================================================

### Established Models and Their Use Cases

* **Medalpaca-13B** (13 billion parameters, ~52 GB)
	+ Application: Copilot for medical reading and healthcare-related information extraction.
	+ Alternative: **BioGPT** by Microsoft (1.5 billion parameters, ~6 GB) – Specialized for biomedical literature understanding and generation.
* **Galactica** by Meta (120 billion parameters, ~480 GB)
	+ Application: Designed to assist with scientific research, including physics.
* **GPT-4** by OpenAI (175 billion parameters, ~700 GB)
	+ Application: Versatile for in-depth analysis across various humanities disciplines.
* **ChatGPT** by OpenAI (20 billion parameters, ~80 GB)
	+ Application: Highly capable in creative writing across genres, including sci-fi.
* **Anthropic's Claude** (52 billion parameters, ~208 GB)
	+ Application: Excels in creative writing with a focus on safety and coherence.
* **CodeLlama** by Meta (16 billion parameters, ~64 GB)
	+ Application: Specialized for code generation and programming assistance.
* **GitHub Copilot** powered by OpenAI Codex (12 billion parameters, ~48 GB)
	+ Application: Assists with code completion and suggestions.
* **Tabnine** ( unknown parameters, unknown file size)
	+ Application: AI-driven code completion tool.
* **StableLM** by Stability AI (7 billion parameters, ~28 GB)
	+ Application: Suitable for generating informal and casual text content.

### Additional Established Models and Their Use Cases

* **OpenAI's GPT-4** (175 billion parameters, ~700 GB)
	+ Application: General-purpose language tasks, including conversation, content creation, summarization, and complex problem-solving.
* **Anthropic's Claude** (52 billion parameters, ~208 GB)
	+ Application: Ethical AI applications requiring safe and aligned responses, suitable for sensitive topics and user interactions prioritizing safety.
* **Meta's LLaMA-2** (13 billion parameters, ~52 GB)
	+ Application: Research and development in natural language understanding and generation, adaptable for various NLP tasks.
* **Stability AI's StableLM** (7 billion parameters, ~28 GB)
	+ Application: Open-source language modeling for tasks like translation, summarization, and creative text generation.
* **Google's PaLM 2** (540 billion parameters, ~2.1 TB)
	+ Application: Complex reasoning, natural language understanding, multilingual applications, and integration into Google services.
* **Cohere's Command R** ( unknown parameters, unknown file size)
	+ Application: Retrieval-based tasks and information retrieval applications, enhancing search and data extraction processes.
* **MosaicML's MPT-7B** (7 billion parameters, ~28 GB)
	+ Application: Customizable language modeling tasks, allowing fine-tuning for specific domains such as finance, healthcare, or education.
* **Hugging Face's Falcon-40B** (40 billion parameters, ~160 GB)
	+ Application: High-performance language generation tasks, producing detailed and coherent text suitable for professional and creative writing.
* **UCL's Gopher** ( unknown parameters, unknown file size)
	+ Application: Knowledge-intensive tasks and research applications requiring deep understanding and comprehensive information synthesis.
* **OpenAI's Codex** (12 billion parameters, ~48 GB)
	+ Application: Code completion, generation, and assistance in software development across multiple programming languages.
* **DeepMind's GopherCite** ( unknown parameters, unknown file size)
	+ Application: Research tasks requiring citation, grounding in academic sources, and synthesis of scholarly information.
* **Salesforce's CodeT5** ( unknown parameters, unknown file size)
	+ Application: Code summarization and generation, supporting multiple programming languages and assisting in code documentation.
* **Aleph Alpha's Luminous** ( unknown parameters, unknown file size)
	+ Application: Multilingual tasks, supporting understanding and generation across different languages for global applications.
* **AI21 Labs' Jurassic-2** ( unknown parameters, unknown file size)
	+ Application: Creative writing, including poetry and storytelling, as well as general NLP tasks like translation and summarization.
* **EleutherAI's GPT-NeoX-20B** (20 billion parameters, ~80 GB)
	+ Application: Open-source projects needing large-scale language models for diverse applications such as research, development, and custom NLP solutions.
* **BigScience's BLOOM** (176 billion parameters, ~704 GB)
	+ Application: Multilingual language tasks, research in language modeling, and applications requiring support for a wide range of languages.
* **Anthropic's Claude-instant** ( unknown parameters, unknown file size)
	+ Application: Real-time conversational agents focused on safety, providing instant and reliable responses in customer service and support scenarios.
* **Replit's Ghostwriter** ( unknown parameters, unknown file size)
	+ Application: Real-time code generation and assistance within development environments, enhancing coding productivity and learning.
* **Google's Bard** ( unknown parameters, unknown file size)
	+ Application: Conversational AI for information retrieval through dialogue, integrating with Google’s search capabilities for up-to-date information.
* **IBM's Watson Assistant** ( unknown parameters, unknown file size)
	+ Application: Enterprise-level chatbots and customer service solutions, integrating with business workflows and providing tailored responses.
* **Sapling's AI Copilot** ( unknown parameters, unknown file size)
	+ Application: Enhancing customer support interactions with AI-driven response suggestions and automation.

### Notes and Recommendations

* **Model Selection**: When choosing a model for a specific application, consider factors such as model size, training data, fine-tuning capabilities, latency, and licensing.
* **Customization**: Many of the above models offer fine-tuning options, allowing them to be tailored further to specific niche applications or industry requirements.
* **Ethics and Safety**: Ensure that the chosen models comply with ethical guidelines and safety standards, especially when dealing with sensitive domains like healthcare, finance, or personal data.
* **Infrastructure**: Assess the computational resources required to deploy and run these models effectively, as larger models may require more robust infrastructure.


