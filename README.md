# Hi, I'm Danil 👋

### Junior AI / LLM Developer | Python | RAG | Backend

I focus on building AI assistants, RAG systems, LLM applications, and Python backend services.

---

## 🧠 AI / LLM

- RAG pipelines
- LangChain
- FAISS
- Sentence Transformers
- Hugging Face Transformers
- Embeddings & Semantic Search
- Prompt Engineering
- Guardrails & Hallucination Mitigation

## 🐍 Python / Backend

- Python
- FastAPI
- REST API
- Pydantic
- PostgreSQL
- SQL
- Postman / Swagger

## 🤖 Machine Learning

- PyTorch
- TensorFlow / Keras
- scikit-learn
- XGBoost
- Pandas
- NumPy
- Variational Autoencoders
- Anomaly Detection

## 🛠 Tools & Engineering

- Git / GitHub
- Docker
- Linux / Windows
- Bash / PowerShell
- API debugging
- Log analysis

---

## 🚀 Featured Projects

### 🔎 Safe RAG Support Assistant

RAG-ассистент для технической поддержки SaaS-продукта с семантическим поиском, контролем источников и защитой от небезопасных запросов.

**Stack:** Python, LangChain, FAISS, Sentence Transformers, Hugging Face Transformers, Qwen2.5, FastAPI, Pydantic

Основные возможности:

- semantic search через FAISS;
- multilingual embeddings;
- локальная LLM;
- source attribution;
- safety guardrails;
- groundedness checks;
- fallback на extractive response;
- RAG tracing;
- REST API на FastAPI.

[Открыть репозиторий →](https://github.com/dkislenko/safe-rag-support-assistant)

---

### 🧠 Russian Headline Fine-Tuning

Экспериментальный NLP-проект по fine-tuning и сравнению **RuGPT3Small** и **ruT5-small** для генерации заголовков русскоязычных новостей.

**Stack:** Python, PyTorch, Hugging Face Transformers, Datasets, Sentence Transformers, SentencePiece, ROUGE

В проекте реализованы:

- baseline evaluation до обучения;
- fine-tuning Causal LM и Seq2Seq моделей;
- контролируемое сравнение на одинаковом количестве данных;
- ROUGE-1 / ROUGE-2 / ROUGE-L;
- semantic similarity;
- анализ длины генераций;
- анализ галлюцинаций;
- сравнение экспериментов на 300 и 1000 training samples.

Контрольный эксперимент на 300 примерах:

| Model | ROUGE-1 | ROUGE-L | Semantic similarity |
|---|---:|---:|---:|
| RuGPT3Small fine-tuned | 0.0753 | 0.0731 | 0.4382 |
| ruT5-small fine-tuned | **0.1384** | **0.1329** | **0.4809** |

[Открыть репозиторий →](https://github.com/dkislenko/russian-headline-finetuning)

---

### 🧬 VAE Anomaly Detection

One-class anomaly detection на Fashion-MNIST с использованием сверточного Variational Autoencoder и reconstruction error.

**Stack:** Python, PyTorch, torchvision, scikit-learn, NumPy, Pandas, Matplotlib

Основные части проекта:

- convolutional VAE;
- one-class training;
- reconstruction error;
- validation-based anomaly threshold;
- ROC / Precision-Recall analysis;
- confusion matrix;
- latent space visualization;
- reconstruction analysis;
- latent interpolation.

Результаты:

| Metric | Score |
|---|---:|
| ROC-AUC | **0.8844** |
| PR-AUC | **0.9840** |
| Precision | **0.9889** |
| Recall | **0.5368** |
| F1 | **0.6959** |

[Открыть репозиторий →](https://github.com/dkislenko/vae-anomaly-detection)

---

## 🎯 Current Focus

Currently exploring and building projects around:

- LLM / RAG applications
- AI assistants
- Retrieval and semantic search
- LLM safety and grounded generation
- Python API services
- Machine learning and anomaly detection

---

## 📫 Contact

- Telegram: [@Kisliiiiy](https://t.me/Kisliiiiy)
- GitHub: [@dkislenko](https://github.com/dkislenko)
