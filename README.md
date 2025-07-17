
# Advanced Prompt Engineering – Workshop Kit

**Duration:** 1.5 hours  
**Audience:** Faculty Development Program

## Quick start

```bash
# clone
git clone https://github.com/yourorg/adv-prompt-eng-workshop.git
cd adv-prompt-eng-workshop

# set up Python env
conda create -n prompts python=3.10 -y
conda activate prompts
pip install -r requirements.txt
```

### Zero‑cost LLM options

1. **Ollama**  
   ```bash
   curl https://ollama.ai/install.sh | sh
   ollama run llama3:8b
   ```
   Then point LangChain to `ollama://localhost`.

2. **Hugging Face Inference Endpoints (free tier)** – limited but good for demo.

3. **LM Studio / Llama.cpp** – local GUI wrappers.

## Repository layout

```
notebooks/    ← executed demo notebooks
slides.md     ← Markdown slides with speaker notes
README.md     ← this file
```

## Exercises

| Level | Topic | Story‑Driven Challenge |
|-------|-------|------------------------|
| Low‑1 | Recursive | Summarise a 3‑paragraph news article below 40 words. |
| Low‑2 | ReAct | Calculate BMI for a set of 5 random users via tool calls. |
| Low‑3 | Chaining | Translate -> sentiment‑analyse 10 tweets. |
| Low‑4 | Embeddings | Build FAQ search over given JSON. |
| Low‑5 | Security | Identify jailbreak strings hidden in user inputs. |
| ...   | ...   | ... (see `exercises.md`) |

Each exercise comes with **starter code** and **solution hints** in the notebook cells.

## Download notebooks into Colab

1. Open <https://colab.research.google.com/>  
2. `File → Open notebook → GitHub`  
3. Paste the repo URL and pick the notebook.

## License

MIT
