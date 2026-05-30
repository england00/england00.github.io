---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Technical Skills
======

- **Languages:** Python, SQL, C++ <br>
- **Cloud/Infrastructure:** AWS SageMaker, Docker, Kubernetes (k9s), Linux, Git, Bash, CI/CD (GitHub Actions) <br>
- **ML/LLM:** PyTorch, Transformers, CUDA (basic), LLM-as-a-judge, SFT/RFT, Prompt optimization, RAG, NLP, Hugging Face, Ollama, MCP, LangGraph, DSPy, Unsloth <br>
- **LLMOps/Experimentation:** Weights & Biases, Langfuse, LiteLLM, OpenAI SDK <br>
- **Backend/APIs**: FastAPI, Flask, Pydantic, REST APIs, MongoDB 


Work Experience
======

## AI Data Trainer – Contractor
**[Cohere Inc.](https://cohere.com/)** – Toronto ON, Canada (Remote) – Part Time <br>
June 2026 - Present

**Key Responsibilities & Contributions:**
- Label, rank, audit, and correct LLM training/evaluation data, adhering to detailed guidelines to ensure high-quality and consistent annotations
- Identify recurring issues and recommend workflow/guideline optimizations
- Provide structured feedback to cross-functional stakeholders to clarify edge cases and reduce annotation ambiguity

## AI Engineer
**[Adeptic Reply (Reply S.p.A.)](https://www.reply.com/adeptic-reply/en)** – Milan, Italy (Hybrid) – Full Time <br>
May 2025 – May 2026

Worked within the IPCEI – Generative AI initiative, an EU-funded large-scale program for advanced AI system development.

**Key Responsibilities & Contributions:**
- Designed and deployed a Reinforcement Fine-Tuning (RFT) pipeline for LLM-as-a-judge systems, integrating rubric design and reward modelling (+10% vs. SFT baselines)
- Built an agentic LLM optimization pipeline using genetic prompt search and adaptive in-context learning (+10–15% performance gains)
- Evaluated continual pre-training and post-training workflows in collaboration with a medical research centre
- Developed a large-scale, modular Python benchmarking pipeline for foundation models on dataset-driven agent tasks
- Led technical reviews and drove optimizations to improve scalability and evaluation robustness across existing agentic systems
- Built an MCP-based server to deploy applications on a private cloud–edge continuum infrastructure, improving deployment consistency and operability
- Designed, implemented, and deployed agentic systems from scratch for cloud–edge continuum support tasks

**Tools & Technologies:**
- **Languages & Frameworks:** Python, FastAPI, Pydantic, MongoDB
- **LLM & GenAI:** OpenAI SDK, LangGraph, MCP, LiteLLM, DSPy, Unsloth
- **Evaluation & Optimization:** Langfuse
- **Infrastructure:** AWS, Docker

## Tutor
**Freelance** – Mantova, Italy – Freelance <br>
October 2021 – September 2024 

Provided private lessons in Mathematics, Physics, and Computer Science to high school students, developing personalized
teaching strategies and helping students improve understanding and exam performance.

## Software Developer – Research Grant 
**[Hipert S.r.l.](https://www.hipert.it/)** – Mantova, Italy – Part Time <br>
April 2022 – September 2022

Cifarelli Project: Applied research in computer vision for robotic pick-and-place with collaborative robots

<div style="text-align: center;">
  <video 
    autoplay 
    muted 
    loop 
    playsinline
    style="
      max-width: 75%;
      height: auto;
      border: 1px solid #ddd;
      padding: 8px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      background-color: white;
    "
  >
    <source src="/videos/video.mp4" type="video/mp4">
  </video>
</div>

**Key Responsibilities & Contributions:**
- Selected and validated vision system architectures for robotic pick-and-place tasks, including depth sensing and image acquisition pipelines for downstream neural network processing
- Created an alternative 6D object pose estimation pipeline based on point cloud convergence from depth measurements, improving robustness in scenarios with randomly arranged objects
- Contributed to the integration of computer vision, 3D perception, and robotic control within a collaborative robot (cobot) environment

**Tools & Technologies:**
- **Languages:** Python, C++
- **Computer Vision & Robotics:** 6D Pose Estimation, RealSense D435i & L515, Iterative Closest Point (ICP)
- **Infrastructure:** Linux, Bash, Docker


Education
======

**M.Sc. in Computer Engineering – Artificial Intelligence Engineering Applications**  
**[University of Modena and Reggio Emilia (UNIMORE)](https://www.unimore.it/en/education/degree-programmes/artificial-intelligence-engineering)** – Modena, Italy  
September 2022 – April 2025  
Master’s program focused on advanced artificial intelligence and machine learning, with strong emphasis on deep learning, 
multimodal learning, and data-driven system design. The program combined rigorous theoretical foundations with applied, 
project-based work across multiple AI domains.  
Final grade: 110/110  

<div style="text-align: center;">
  <img 
    src="/images/MethWayOS.png"
    style="
      max-width: 100%;
      height: auto;
      border: 1px solid #ddd;
      padding: 8px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      background-color: white;
    "
  >
</div>
Thesis: **MethWayOS: A new interpretable Deep Learning method for Gene Expression and Methylation based Cancer OS**  

**Erasmus+ Exchange Program**  
**[Norwegian University of Science and Technology (NTNU)](https://www.ntnu.edu/)** – Trondheim, Norway  
January 2024 – June 2024  
International exchange program focused on communication networks, robotics, and cooperative technologies. Completed 
coursework in mobile networks, robot modeling and control, social media systems, and secure communication infrastructures 
within a highly research-oriented environment.  

**B.Sc. in Computer Engineering – Industry 4.0**  
**[University of Modena and Reggio Emilia (UNIMORE)](https://www.unimore.it/en/education/degree-programmes/computer-engineering-dm27004)** – Mantova, Italy  
September 2019 – October 2022  
Bachelor’s degree providing a strong foundation in computer engineering, including algorithms, software engineering, control 
systems, and industrial automation. The Industry 4.0 track emphasized cyber-physical systems, embedded software, and data-driven 
industrial applications.  
Final grade: 110/110 with honors  

<div style="text-align: center;">
  <img 
    src="/images/RANSAC+ICP.png"
    style="
      max-width: 60%;
      height: auto;
      border: 1px solid #ddd;
      padding: 8px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      background-color: white;
    "
  >
</div>
Thesis: **Using a neural network and a depth-based algorithm for 6D pose estimation**  

**High School Diploma – Applied Sciences**  
**[Liceo Scientifico Belfiore](https://www.liceobelfioremantova.edu.it/)** – Mantova, Italy  
September 2014 – June 2019  
Final grade: 94/100


Projects
======

**[MethWayOS](https://github.com/england00/MethWayOS)**  
A co-attention–based multimodal model for cancer survival prediction by integrating RNA gene expression and DNA promoter methylation data.  
**Tech stack**: Python, PyTorch, CUDA, Pandas, NumPy

**[Supervisor Node for Vehicle Control](https://github.com/england00/SupervisorNode)**  
ROS2-based supervisor node using a finite state machine (FSM) to monitor vehicle health and publish system states as ROS topics.  
**Tech stack**: C++, ROS2

**[PastaBot – Collaborative Pick-and-Place System](https://github.com/england00/SmartRoboticsPastaBot)**  
Example of an industrial pick-and-place workflow with a collaborative robot for sorting packages based on weight using a force sensor, integrating motion planning and perception.  
**Tech stack**: Python, ROS, Gazebo, MoveIt, OpenCV  

**[MQTTtoDB – Telemetry Ingestion Pipeline](https://github.com/england00/MQTTtoDB)**  
MQTT client for collecting telemetry and control data from distributed robotic systems and persisting it into a MySQL database.  
**Tech stack**: Python, MQTT, MySQL 

**[RESTful HTTP API for Robotic Telemetry](https://github.com/england00/RESTfulHttpAPI)**  
A RESTful API to expose telemetry and system data from robotic infrastructures stored in a local MySQL database.  
**Tech stack**: Python, Flask, MySQL

[Other projects available here](https://github.com/england00?tab=repositories)


Languages
======

Italian (Native)  
English (Fluent)
