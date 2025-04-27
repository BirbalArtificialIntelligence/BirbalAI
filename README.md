# Birbal AI
Comprehensive tech stack details for Birbal AI

# Birbal AI

Birbal AI proposes an inclusive, scalable, and innovative suite of tools leveraging AI, blockchain, and gamified learning to combat misinformation, enhance digital literacy, and ensure data security. Our mission is to empower individuals and communities with cutting-edge technologies to foster trust, transparency, and critical thinking.

---

## 🌟 Key Solutions

### 1. **FactCheckPlay**
   - **Description**: A gamified platform where youth learn to identify and counter misinformation through interactive challenges.
   - **Features**:
     - Supports multiple formats: audio, video, images.
     - Available in 22+ Indian languages.
     - Fosters critical thinking and media literacy.
   - **Impact**: Designed to educate and empower the next generation to tackle misinformation creatively.

### 2. **DeepShield AI**
   - **Description**: AI-powered detection system for real-time validation of content.
   - **Features**:
     - Identifies deepfakes and manipulated content.
     - Tracks misinformation sources.
     - Ensures real-time content validation.
   - **Impact**: Enhances trustworthiness of shared information by combating disinformation effectively.

### 3. **DataTrust Blockchain**
   - **Description**: A decentralized protocol for content watermarking and data provenance.
   - **Features**:
     - Safeguards data against unauthorized alterations.
     - Provides legitimacy to shared information.
     - Blockchain-backed provenance tagging.
   - **Impact**: Ensures the authenticity and security of digital content.

### 4. **TrustCrowd**
   - **Description**: A crowd-powered social network tool for collective misinformation monitoring.
   - **Features**:
     - Allows users to report and verify data collaboratively.
     - Promotes peer-driven trust through social validation.
   - **Impact**: Empowers communities to actively combat misinformation at scale.

---

## 🎯 Tech Stack

### 📌 Frontend

| Component    | Role                                      | Status             | Licensing     |
|--------------|-------------------------------------------|--------------------|---------------|
| React.js     | Main UI framework                        | Under Development  | MIT License   |
| Tailwind CSS | Styling framework                        | Complete           | MIT License   |
| Next.js      | Server-side rendering and routing        | Complete           | MIT License   |
| JQuery       | Used for legacy module integration       | Limited Use        | MIT License   |
| I18next      | Internationalization and localization    | In Integration     | MIT License   |

### 📌 Backend

| Component           | Role                                              | Status             | Licensing         |
|---------------------|---------------------------------------------------|--------------------|-------------------|
| Node.js             | Server environment for APIs                      | Complete           | MIT License       |
| Express.js          | Web framework for APIs                           | Complete           | MIT License       |
| PostgreSQL          | Primary relational database                      | Operational        | Open Source       |
| MongoDB             | NoSQL database for unstructured content          | Operational        | SSPL              |
| Redis               | In-memory cache and message queues               | Operational        | BSD 3-Clause      |
| Hugging Face        | Hosting transformer-based NLP models             | In Testing         | Apache 2.0        |
| TensorFlow Serving  | Model inference microservice                     | Under Development  | Apache 2.0        |
| Hyperledger Fabric  | Blockchain content provenance layer              | MVP Complete       | Apache 2.0        |
| RabbitMQ            | Messaging and task queues for moderation workflows | In Testing         | MPL 2.0           |
| Docker              | Containerization                                 | Operational        | Apache 2.0        |
| Kubernetes          | Container orchestration                          | Operational        | Apache 2.0        |

### 📌 Meta / ML Pipeline

| Component                 | Role                                        | Status             | Licensing         |
|---------------------------|---------------------------------------------|--------------------|-------------------|
| Python (scikit-learn, pandas, spaCy) | Model development and preprocessing | Active             | Various Permissive |
| Hugging Face Transformers | Multilingual NLP model fine-tuning         | Active             | Apache 2.0        |
| Label Studio             | Data annotation with human review           | Active             | Apache 2.0        |
| MLflow                   | Experiment tracking and model versioning    | Operational        | Apache 2.0        |
| AWS S3                   | Training data storage                       | Operational        | Proprietary (AWS) |
| AI Ethics Auditing Toolkit | Proprietary fairness, bias, and explainability tools | Under Development | Proprietary       |

---

## 📄 API and Documentation

### System Documentation
- Internal Confluence-based documentation outlining module architecture, endpoints, model specs, and database schemas (Confidential).

### Process Documentation
- GitHub Wiki covering CI/CD pipelines, data labeling protocols, and model retraining processes.

### User Documentation
- Planned for public platform launch (Q4 Year 1) via web-based knowledge hub.

### API Documentation
- OpenAPI 3.0-compliant documentation using Swagger UI for moderation APIs and public dashboards (Planned Q3 Year 1).

---

## 📖 Licensing and Open Source Intentions

- **Open Source (Apache 2.0 / MIT / GPLv3):**  
  All AI moderation engines, blockchain provenance tools, and crowd moderation APIs after Q4 Year 1, post-stabilization.

- **Proprietary:**  
  AI personalization reports, enterprise analytics dashboards, and AI Ethics Toolkit to be retained as commercial IP.

- **Open Source Exceptions:**  
  Frontend, multilingual UI, moderation workflows to be released progressively under MIT / Apache 2.0.

---

## 🌐 Contribution Guidelines
Contributions are welcome! Please refer to the `CONTRIBUTING.md` file for details on the process for submitting pull requests and reporting issues.

---

## 🚀 Contact
For inquiries or requests for documentation, please reach out via the repository's issue tracker or email.
