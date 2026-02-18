---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Work Experience
======
## AI Engineer
**[Adeptic Reply (Reply S.p.A.)](https://www.reply.com/adeptic-reply/en)** – Milan (Hybrid), Italy  
May 2025 – Present

Working within the IPCEI – Generative AI initiative, an EU-funded large-scale program for advanced AI system development.

**Key Responsibilities & Contributions:**
- Designed and implemented a Reinforcement Fine-Tuning (RFT) pipeline for LLM-as-a-Judge systems with rubric engineering, reward modeling, and automated grader evaluation, improving judgment accuracy by ~10% over SFT baselines
- Built an agentic LLM optimization pipeline using genetic prompt optimization and adaptive in-context learning, achieving 10–15% performance gains
- Evaluated training stacks for Continual Pre-Training and Post-Training workflows in collaboration with a leading Italian medical research center
- Engineered a modular Python pipeline for benchmarking foundation models on dataset-driven agent tasks
- Drove technical reviews and defined optimization strategies for pre-existing agentic AI systems, enhancing scalability and evaluation robustness

**Tools & Technologies:**
- **Languages & Frameworks:** Python, FastAPI, UV
- **LLM & GenAI:** OpenAI Platform & SDK, LangGraph, MCP, RAG, Hugging Face
- **Evaluation & Optimization:** Langfuse, GEPA, Unsloth
- **Infrastructure:** AWS, Docker

## Tutor
**Freelance** – Mantova, Italy  
October 2021 – September 2024 

Provided private lessons in Mathematics, Physics, and Computer Science to high school students, developing personalized
teaching strategies and helping students improve understanding and exam performance.

## Software Developer – Research Grant 
**[Hipert S.r.l.](https://www.hipert.it/)** – Mantova, Italy
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



Techinal Skills
======

**Programming Languages:** Python, C++, SQL  
**LLM & GenAI:** LLM evaluation pipelines, LLM-as-a-Judge systems, Supervised Fine-Tuning (SFT), Reinforcement Fine-Tuning (RFT), Prompt Optimization, OpenAI SDK, LiteLLM, LangGraph, DSPy, Langfuse, Retrieval-Augmented Generation (RAG), Hugging Face  
**ML & AI:** Deep Learning, Multimodal Learning, Model Evaluation, Reward modeling, Continual Pre-Training & Post-Training workflows  
**Robotics & Perception:** Pick-and-Place Systems, Depth Sensing, 3D Computer Vision, 6D Pose Estimation  
**Backend & APIs**: RESTful API, FastAPI, Flask, Pydantic  
**Cloud & Infrastructure:** Amazon Web Services, Docker, Linux, Bash, Git  



Languages
======

Italian (Native)  
English (Fluent)
