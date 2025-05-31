# RAG-Internal-Knowledge-Assistant

This internal AI assistant reduces human workload by answering employee questions using company documents through Retrieval-Augmented Generation (RAG).

    Java 17 is used to write core backend logic and services.
    
    Spring Boot structures the entire application and exposes REST APIs.
    
    Spring Web defines HTTP endpoints like /ask, /upload, and /health.
    
    Spring Security with JWT secures the assistant so only authorized employees can access it.
    
    Spring Data JPA manages persistence of users, documents, embeddings, and logs in the database.
    
    PostgreSQL stores structured data like user queries and document metadata.
    
    pgvector allows semantic vector search by storing OpenAI embeddings for internal documents.
    
    Apache Tika extracts raw text from uploaded PDFs, DOCX, TXT, and HTML files.
    
    OpenAI Tokenizer ensures that text chunks fit within model context limits.
    
    Spring AI integrates with the OpenAI API to send prompts and receive AI-generated answers.
    
    OpenAI API (GPT-4/3.5) powers the assistant's natural language answers using RAG context.
    
    LangChain4j optionally structures complex prompt flows and RAG chains.
    
    Lombok reduces boilerplate code in DTOs, entities, and services.
    
    Maven manages all dependencies such as OpenAI SDK, Spring modules, and pgvector.
    
    Docker containerizes the Java app, database, and vector storage.
    
    Docker Compose runs the entire stack locally or in the cloud with one command.
    
    GitHub Actions automates building, testing, and deploying the application.
    
    Render, Railway, or Fly.io deploy the assistant for public or private demos.
    
    Spring Boot Actuator exposes metrics and health check endpoints.
    
    Grafana + Prometheus (optional) monitor system metrics like latency and usage.
    
    ELK Stack (optional) logs and analyzes user queries for insights.
    
    Spring Scheduled Jobs handle document re-embedding and periodic tasks.
    
    Airflow or cron (optional) orchestrate more advanced RAG workflows.
    
    JUnit + Mockito test services like parsing, search, and prompt response accuracy.
    
    Testcontainers spin up isolated PostgreSQL and pgvector containers for integration tests.
    
    Springdoc / Swagger auto-generate OpenAPI docs for endpoints like /ask and /upload.
    
    Postman is used to test and share API usage collections.
    
    Git tracks all source code changes with version control.
    
    GitHub hosts the project and enables collaboration or public showcasing.
    
    README.md explains setup, usage, and architecture of the assistant.
    
    Demo GIFs and videos show how the assistant works in real-time.
    
    GitHub Projects and Issues display planning and feature tracking like a real team project.
    
    
