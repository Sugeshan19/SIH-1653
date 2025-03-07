# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea


## Proposed Solution / Architecture Diagram

![Screenshot 2025-03-06 113639](https://github.com/user-attachments/assets/dff4c03e-4c24-4488-84d1-8ab0f30d1e96)


## Use Cases

1. Expert Conducting Interview
2. AI-Based Question & Answer Relevance Analysis
3. Performance Scoring & Analytics
4. Security & Access Control
5. Automated Bias Detection in Interviews
6. Candidate Mock Interview & Preparation Mode
7. Post-Interview Reporting & Insights for Experts
8. Question Bank Management & Continuous Learning
9. Multi-Level Interview Process Management

## Technology Stack

1. Frontend (User Interface)
    Frameworks/Libraries: React.js, Next.js (for fast rendering), Tailwind CSS (for styling)
    Real-time Communication: WebRTC (for video interviews), Socket.io (for real-time interactions)
    UI Components: ShadCN/UI, Material-UI
2. Backend (API & Business Logic)
    Framework: Node.js (Express.js) or Django (Python)
    Authentication: OAuth 2.0, JWT (JSON Web Token)
    Real-time Data Processing: WebSockets, Kafka (for high-volume streaming data)
    Microservices Architecture: Docker & Kubernetes
3. AI & NLP (Interview Assessment Engine)
    Language Processing: OpenAI GPT models, BERT (for question & answer relevance scoring)
    Speech Analysis: Google Speech-to-Text, IBM Watson Speech API
    Sentiment & Bias Detection: Transformers (Hugging Face), NLTK, Spacy
    Scoring Algorithm: TensorFlow, PyTorch
4. Database & Storage
    Primary Database: PostgreSQL / MySQL (structured data)
    NoSQL Database: MongoDB (for storing user responses and interview logs)
    Caching: Redis (for fast retrieval of frequently used questions)
    Cloud Storage: AWS S3 / Google Cloud Storage (for video interview recordings)
5. Security & Compliance
    Authentication & Role-Based Access Control (RBAC): Keycloak, Auth0
    Encryption: AES-256, TLS 1.3 (for securing interview data)
    DRDO Compliance: Adherence to MoD security protocols, VPN-based restricted access


## Dependencies

