# GenieAI 🤖✨

GenieAI is a ChatGPT-like AI chatbot built using Java and Spring Boot.  
The application enables users to search or ask questions and receive intelligent, AI-powered responses through a REST-based backend system.

---

## 🧠 Project Overview
GenieAI functions as an intelligent conversational chatbot:
- Accepts user queries or search requests
- Processes requests using backend business logic
- Returns meaningful, structured responses
- Designed with a scalable and clean layered architecture

---

## 🛠️ Tech Stack
- Java
- Spring Boot
- REST APIs
- Maven
- Docker
- IntelliJ IDEA

---

## 📂 Project Architecture
controller → Handles chatbot API requests
service → Core chatbot logic & processing
repo → Data access layer
entity → Request/Response models
config → Application configuration
cache → Performance optimization


---

## ⚙️ Key Features
- ChatGPT-like conversational experience
- Search-based query handling
- RESTful API design
- Clean layered backend architecture
- Dockerized application setup
- Easily extendable for future AI integrations

---

## ▶️ How to Run the Application

### Step 1: Clone Repository
```bash
git clone https://github.com/your-username/GenieAI.git

Step 2: Navigate to Project
cd GenieAI

Step 3: Run Application
mvn spring-boot:run


🔌 Sample API Usage
Endpoint
POST /api/chat

Request
{
  "query": "What is Spring Boot?"
}


Response
{
  "answer": "Spring Boot is a Java framework used to build standalone applications."
}


🐳 Docker Support
docker build -t genieai-chatbot .
docker run -p 8080:8080 genieai-chatbot

🎯 Learning Outcome

AI chatbot backend architecture

Spring Boot REST API development

Request–response handling

Scalable backend design

Real-world project structuring

👨‍💻 Author

Piyush Aswani


