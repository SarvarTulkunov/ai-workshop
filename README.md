# 🧠 AI Workshop

Welcome to **AI Workshop** — a collection of hands-on AI projects demonstrating practical implementations with **Java**, **Spring AI**, and **Model Context Protocol (MCP)**.  
Whether you’re exploring **chatbots**, **multimodal AI**, **RAG (Retrieval-Augmented Generation)**, or building **MCP servers**, this repository has you covered.

---

## 📂 Repository Structure

### **1. `java-ai-workshop`**
> Covers essential AI topics in Java using Spring AI.

**Features:**
- 💬 **Chat** — Build conversational AI with contextual responses.
- 🧠 **Memory** — Implement AI memory for better context retention.
- 🎨 **Multimodal** — Work with text + images for richer AI interactions.
- 🔧 **Tools** — Extend AI capabilities with custom tools.
- ✍ **Prompts** — Master prompt engineering for more accurate outputs.

---

### **2. `rag-with-spring-ai`**
> Two complete approaches to **Retrieval-Augmented Generation (RAG)**.

**Approach 1:** Save processed data into **files** for retrieval.  
**Approach 2:** Store and query data using a **Vector Database** for scalable semantic search.

**Use cases:**
- AI question answering from custom documents
- Knowledge-based assistants
- Search-enhanced chatbots

---

### **3. `spring-io-mcp-sse`**
> MCP (**Model Context Protocol**) server implementation using **Server-Sent Events (SSE)**.

**Highlights:**
- Real-time AI updates via SSE
- Great for streaming responses
- Ideal for integrating live AI results into applications

---

### **4. `spring-io-mcp-stdio`**
> MCP server with **Standard Input/Output (STDIO)** communication.

**Highlights:**
- Lightweight MCP integration
- No need for complex networking
- Perfect for CLI-based AI tools

---

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/SarvarTulkunov/ai-workshop.git
cd ai-workshop
```

2. **Explore each project**
```bash
cd java-ai-workshop
# or
cd rag-with-spring-ai
```

2. **Run the project**
```bash
./mvnw spring-boot:run
```


🛠 Technologies Used
- Java 17
- Spring Boot 3.5.4
- Spring AI
- Vector Databases (e.g., PGVector, Pinecone, etc.)
- Model Context Protocol (MCP)
- Server-Sent Events (SSE)


📌 Purpose
This repository is designed for learning and experimenting with AI integrations in real-world Java applications.
By going through these projects, you’ll learn how to:

- Integrate AI models into applications
- Build RAG pipelines for knowledge-based AI
- Create MCP servers for AI-assisted tooling
- Work with multimodal data in Java
