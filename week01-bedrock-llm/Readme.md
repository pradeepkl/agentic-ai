# 📚 Week 1 – Core LLM & AWS Bedrock

**Goal:**  
Set up AWS Bedrock, master basic LLM usage, learn prompt engineering, work with multiple models, and understand the vector math behind embeddings.

**Daily Commitment:** ~6 hours/day (study + hands-on)

---

## 📅 Day-by-Day Plan

### **Day 1 – AWS Bedrock Setup & First API Call**
- Enable AWS Bedrock in console
- Create IAM role & policy for Bedrock access
- Install AWS CLI & configure credentials
- Install Python SDK (`boto3`)
- List available Bedrock models
- Call Anthropic Claude 3 Haiku with a basic prompt

**Deliverable:**  
`bedrock_hello.py` — prints model output for a test prompt.

---

### **Day 2 – Prompt Engineering Basics**
- Understand zero-shot, few-shot, system prompts
- Role, context, task, constraints in prompts
- Test same query across Claude, Mistral, Titan
- Optimize prompt tone, style, detail

**Deliverable:**  
`prompt_experiments.py` — runs same prompt across multiple models and logs output.

---

### **Day 3 – Model Parameters & Output Control**
- Learn temperature, maxTokens, stopSequences, topP
- Tune temperature for creativity vs determinism
- Limit tokens for cost control
- Create CLI tool to accept prompt + parameters

**Deliverable:**  
`bedrock_cli.py` — accepts user input and model parameters.

---

### **Day 4 – Working with Multiple Models**
- Model IDs & switching in code
- Claude vs Mistral vs Titan strengths
- Benchmark tasks across models (summarization, creative writing, classification)
- Create “model selector” script

**Deliverable:**  
`model_selector.py` — picks optimal model based on task type.

---

### **Day 5 – Introduction to Embeddings**
- What embeddings are & why they matter
- Vector math basics (dot product, norms, cosine similarity)
- Generate embeddings with Titan
- Build in-memory semantic search

**Deliverable:**  
`semantic_search.py` — stores text embeddings & retrieves similar items.

---

### **Day 6 – Streaming Responses & Real-Time Chat**
- Streaming API concept & use cases
- Implement streaming with Claude 3 Haiku
- Build terminal-based chat app

**Deliverable:**  
`bedrock_chat.py` — chat app with streaming output.

---

### **Day 7 – Week 1 Project & Review**
- Recap all concepts learned
- Build **Prompt Playground**:
  - Select model from dropdown
  - Input prompt & parameters
  - Display output & cost estimate
- Review math concepts for Week 2 (cosine similarity, embeddings)

**Deliverable:**  
`prompt_playground.py` — mini-app for experimenting with models & prompts.

---

---

## 🛠 Tech Stack for Week 1
- **Language:** Python 3.10+
- **SDK:** boto3
- **AWS Services:** Bedrock, IAM
- **Libraries:** requests, numpy (for cosine similarity), rich (for CLI output formatting)

---

## 🎯 Outcomes by End of Week 1
- AWS Bedrock environment set up & tested
- Proficiency in prompt engineering basics
- Ability to switch between and benchmark LLM models
- Understanding of embeddings & cosine similarity
- Working mini-app for experimenting with prompts and models

---

## 📖 Recommended References
- [AWS Bedrock Documentation](https://docs.aws.amazon.com/bedrock/)
- [boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

