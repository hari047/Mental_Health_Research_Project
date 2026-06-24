<div align="center">

  <h1>Predicting Mental Health Recovery Trajectories in Longitudinal Forum Data</h1>
  <h3>An NLP and Machine Learning Framework</h3>

</div>

---

### Introduction

#### The Escalating Mental Health Crisis and Access Barriers
- Mental health has emerged as a paramount global concern, significantly exacerbated by the COVID-19 pandemic. According to the World Health Organization (2022), the pandemic triggered a 25% surge in adult anxiety and depression worldwide, a crisis that increasingly affects younger demographics as well. Unfortunately, accessing immediate professional care is a major hurdle. Therapists and psychiatrists frequently have long waitlists, leaving immediate help out of reach for many. While Australia offers various mental health crisis hotlines, these services are often restricted to brief, 20-minute consultations with on-call professionals, which may not be enough for long-term or complex needs.

<div align="center">
  <img width="400" height="250" alt="images" src="https://github.com/user-attachments/assets/2faf9d18-4a2c-4d1b-9e52-d8afb4e6322a" />
  <img width="400" height="250" alt="images" src="https://raisely-images.imgix.net/beyond-bitumen/uploads/infographic-over-2-in-5-people-mental-health-condition-jpg-c6dde3.jpg" />
</div>


#### The Role and Risks of Online Forums
- To bridge this gap in care, many individuals turn to online communities like Beyond Blue and Reddit. The anonymity of an online persona creates a safe, judgment-free environment where people feel comfortable detailing their struggles and seeking advice from both peers and professionals (Calvo et al., 2017). For Australians struggling to secure prompt psychiatric appointments, these digital spaces offer vital, immediate community support.

- However, the massive scale and open nature of these platforms create significant operational challenges. Human moderators are frequently overwhelmed by high volumes of posts, leading to substantial backlogs and delayed responses. This delay introduces a critical vulnerability: users in acute distress might experience severe panic or engage in self-harm during the waiting period before professional intervention or moderation occurs.

#### My Solution for Early Intervention
- To overcome these moderation bottlenecks, automated triage systems are being explored as a scalable solution. By leveraging Machine Learning (ML) and Natural Language Processing (NLP) algorithms, platforms can rapidly analyze user text to flag high-risk posts, ensuring early intervention and helping to prevent tragedies before human moderators can step in.

---

### The Project has been split into two parts:
#### Project A:
|             Phase             |                      Work                    | 
| :---------------------------: | :------------------------------------------: |
|               1               |  Formulate Research Questions and Objectives | 
|               2               |  Literature Review                           | 
|               3               |  Dataset Exploration                         |
|               4               |  Initial Model implementation                | 

Check out the Notebook [Mental Health Trajectories Project A](Mental_Health_Trajectories_PartA.ipynb) for Project A.

#### Project B:
|             Phase             |                       Work                          | 
| :---------------------------: | :-------------------------------------------------: |
|               1               | Fixing the Target Labels                            | 
|               2               | Advanced Feature Engineering                        | 
|               3               | Handling Class Imbalance                            | 
|               4               | Baseline Validation                                 |
|               5               | Hyperparameter Tuning                               | 
|               6               |	Deep NLP Expansion                                  | 
|               7               |	Sparsity Diagnosis                                  | 
|               8               |	XGBoost Implementation                              | 

---


