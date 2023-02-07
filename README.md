# Google Summer of Code 2023

<p align="center">
<img src="https://jina.ai/assets/images/logo.svg" alt="GSoC banner" width="20%" >
</p>


<p align="center">
<b>
X
</b>
</p>


<p align="center">
<img src="https://summerofcode.withgoogle.com/assets/media/logo.svg" alt="GSoC banner" width="60%" >
</p>

Join the Jina AI team for a summer full of coding, learning and fun. Be part of our diverse community! Read more about the program and apply at the [Google Summer of Code website.](https://summerofcode.withgoogle.com/)

**Note｜GSoC 2023 change**: Contributors are now eligible if you are either Free-software newcomers or students (one of the two criteria fulfilled).

**Dates | GSoC 2023 Timeline**:

- February 22, 2023 - Accepted mentoring organizations get announced
- March 20, 2023 - Applications open for contributors
- April 4, 2023 - Deadline for contributors to apply

**More Information**: Read the [GSoC Manual](https://google.github.io/gsocguides/student/), [Timeline](https://developers.google.com/open-source/gsoc/timeline), and [GSoC FAQs](https://developers.google.com/open-source/gsoc/faq)

If you have questions, please feel free to reach out to us on [Slack](https://jina.ai/slack/) or [GitHub discussions](https://github.com/docarray/docarray/discussions). 



## 🔎 Who are we?

<p align="center">
<b>
Welcome to the GSoC projects page of Jina AI! 
</b>
</p>

[Jina AI](https://jina.ai) provides a powerful platform for building neural-search, generative AI services with cloud-native technology, and we are thrilled to participate in Google Summer of Code (GSoC) this year. Our goal is to provide students with opportunities to work on real-world, cutting-edge projects and contribute to the growth of our community.

We are firm supporters of open source and have open sourced multiple projects, including:

- [Jina](https://github.com/jina-ai/jina) is a MLOps framework that empowers anyone to build multimodal AI services via cloud native technologies. It uplifts a local PoC into a production-ready service. Jina handles the infrastructure complexity, making advanced solution engineering and cloud-native technologies accessible to every developer. Check out the [documentation](https://docs.jina.ai/)!
- [DocArray](https://github.com/docarray/docarray) is a library for nested, unstructured, multimodal data in transit, including text, image, audio, video, 3D mesh, etc. It allows deep-learning engineers to efficiently process, embed, search, recommend, store, and transfer multimodal data with a Pythonic API. and [DocArray is now hosted under the Linux Foundation AI & Data.](https://jina.ai/news/donate-docarray-lf-for-inclusive-standard-multimodal-data-model/)  Check out the [documentation](https://docs.docarray.org/) and [roadmap](https://github.com/docarray/docarray/issues/780)!

We are always enthusiastic about GSoC and we believe this experience will help us empower more users, improve open source and overall, enhance developer experience. 



## 💡 Project ideas


| Title                                                        | Skills needed                             | Mentors                                                      | Difficulty | Size      |
| ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ | ---------- | --------- |
| [Build Executor (model) UI in jina](https://github.com/jina-ai/GSoC#project-idea-4-build-executor-model-ui-in-jina) | Python                                    | @[Alaeddine Abdessalem](https://github.com/alaeddine-13), , @[Philip Vollet](https://www.linkedin.com/in/philipvollet) | Easy       | 175 hours |
| [DocArray wrap ANN libraries](https://github.com/jina-ai/GSoC#project-idea-1-docarray-wrap-ann-libraries) | Python, ANN Search experience             | @[Johannes](https://github.com/JohannesMessner), @[Sami Jaghouar](https://github.com/samsja), @[Philip Vollet](https://www.linkedin.com/in/philipvollet) | Medium     | 175 hours |
| [Research about deploying LLM with Jina](https://github.com/jina-ai/GSoC#project-idea-3-research-about-deploying-llm-with-jina) | Python, Pytorch, CUDA, docker, Kubernetes | @[Alaeddine Abdessalem](https://github.com/alaeddine-13), @[Joan Martínez](https://github.com/JoanFM) | Medium     | 350 Hours |
| [Expand ANNLite capabilities with BM25 to build Hybrid Search](https://github.com/jina-ai/GSoC#project-idea-5--expand-annlite-capabilities-with-bm25-to-build-hybrid-search) | Python, C++, Lucene, ANN, Inverted Index  | @[Felix Wang](https://github.com/numb3r3), @[Joan Martínez](https://github.com/JoanFM), @[Girish Chandrashekar](https://github.com/girishc13) | Hard       | 350 hours |
| [Make ANNLite the go-to Vector Search library to be scaled by Jina using the StatefulExecutor feature](https://github.com/jina-ai/GSoC#project-idea-2-make-annlite-the-go-to-vector-search-library-to-be-scaled-by-jina-using-the-statefulexecutor-feature) | ANN, C++, Python, Databases               | @[Felix Wang](https://github.com/numb3r3), @[Joan Martínez](https://github.com/JoanFM) | Hard       | 350 Hours |
| [JAX support in DocArray v2](https://github.com/jina-ai/GSoC#project-idea-6--expand-annlite-capabilities-with-bm25-to-build-hybrid-search) | Python, AI/ML, JAX Framework experience   | @[Sami Jaghouar](https://github.com/samsja)                  | Hard       | 350 Hours |



### *Project idea 1: Build Executor (model) UI in jina*

| info             | details                                                      |
| ---------------- | ------------------------------------------------------------ |
| Skills needed    | Python                                                       |
| Project size     | 175 hours                                                    |
| Difficulty level | Easy                                                         |
| Mentors          | @[Alaeddine Abdessalem](https://github.com/alaeddine-13), @[Philip Vollet](https://www.linkedin.com/in/philipvollet) |

#### Project Description

- Jina Executors are components that perform certain tasks and expose them as services using gRPC. Executors accept DocumentArrays as input and output. However, with DocArray v2 focusing on type annotations and enabling annotation of executor endpoints, it becomes possible for executors to describe their services and input/output in the same way as OpenAPI schemas. This allows us to offer built-in UIs for executors, enabling people to easily use their services with multi-modal data. The goal is to build this feature in Jina using Gradio.

#### Expected outcomes

- Submit one or more Pull Requests (PRs) to the Jina repository that enables providing a built-in Executor UI for Executors. The UI can be built using Gradio and should be able to infer information about the Executor service using type annotations.



### *Project idea 2: DocArray wrap ANN libraries*

| Info             | details                                                      |
| ---------------- | ------------------------------------------------------------ |
| Skills needed    | Python, ANN Search experience                                |
| Project size     | 175 hours                                                    |
| Difficulty level | Medium                                                       |
| Mentors          | @[Johannes](https://github.com/JohannesMessner), @[Sami Jaghouar](https://github.com/samsja), @[Philip Vollet](https://www.linkedin.com/in/philipvollet) |

#### Project Description

- In DocArray, we have been concentrating on developing production-ready Vector DBs for large-scale searches. However, there are many ANN libraries without scalability layers that can be integrated into DocArray, making it accessible to academia and production teams with small-to-medium amounts of data, without the need for external services.

#### Expected outcomes

- We have a set of DocStores implementations in DocArray that support the most popular ANN libraries, such as FAISS, Annoy, and Hnswlib.



### *Project idea 3: Research about deploying LLM with Jina*

| info             | details                                                      |
| ---------------- | ------------------------------------------------------------ |
| Skills needed    | Python, Pytorch, CUDA, docker, Kubernetes                    |
| Project size     | 350 hours                                                    |
| Difficulty level | Hard                                                         |
| Mentors          | @[Alaeddine Abdessalem](https://github.com/alaeddine-13), @[Joan Martínez](https://github.com/JoanFM) |

#### Project Description

- Recently, large language models (LLMs) have gained attention for their ability to generate text to solve various tasks, such as question-answering, reading comprehension, and coding. However, most of these models are quite large, and deploying them requires certain technologies to be in place to enable scalability when using GPU resources. We aim to assess the capability of deploying such models with Jina and explore what integrations we can build with the existing ecosystem to enable LLM inference using the Jina stack.

#### Expected outcomes

- Jina is ready to be used to deploy and scale LLM to build Generative applications in a cost-efficient manner




### *Project idea 4:  Expand ANNLite capabilities with BM25 to build Hybrid Search*

| info             | details                                                      |
| ---------------- | ------------------------------------------------------------ |
| Skills needed    | Python, C++, Lucene, ANN, Inverted Index                     |
| Project size     | 350 hours                                                    |
| Difficulty level | Hard                                                         |
| Mentors          | @[Felix Wang](https://github.com/numb3r3) @[Joan Martínez](https://github.com/JoanFM) @[Girish Chandrashekar](https://github.com/girishc13) |

#### Project Description

- In relation to [Research about deploying LLM with Jina](https://github.com/jina-ai/GSoC#project-idea-3-research-about-deploying-llm-with-jina) project, another interesting approach would be to incorporate BM25 and Hybrid Search into ANNLite, which would enable Jina to build scalable Hybrid Search solutions in the cloud with a powerful default solution.

#### Expected outcomes

- ANNLite is ready to be used as a default library to solve Hybrid Search applications.



### *Project idea 5: Make ANNLite the go-to Vector Search library to be scaled by Jina using the StatefulExecutor feature*

| info             | details                                                      |
| ---------------- | ------------------------------------------------------------ |
| Skills needed    | ANN, C++, Python, Databases                                  |
| Project size     | 350 hours                                                    |
| Difficulty level | Hard                                                         |
| Mentors          | @[Felix Wang](https://github.com/numb3r3) @[Joan Martínez](https://github.com/JoanFM) |

#### Project Description

- Jina is developing a stateful executor feature that enables Deployments with a state to be replicated and scaled. This opens the door to having a Vector Database in our ecosystem effectively and robustly. Iterating on ANNLite to act as the "Lucene" for Jina would be a great opportunity.

#### Expected outcomes

- Prove and come up with an Executor in our Hub that uses ANNlite or DocArray with ANNLite as a backend to be the default Vector Databases for all our examples for mid-sized data requirements.



### *Project idea 6:  JAX support in DocArray v2*

| info             | details                                     |
| ---------------- | ------------------------------------------- |
| Skills needed    | Python, C++, Lucene, ANN, Inverted Index    |
| Project size     | 350 hours                                   |
| Difficulty level | Hard                                        |
| Mentors          | @[Sami Jaghouar](https://github.com/samsja) |

#### Project Description

- DocArray is a library for representing, sending, and storing multi-modal data, with a focus on applications in ML and Neural Search. It currently supports several deep learning frameworks, including PyTorch and TensorFlow. Jax is becoming increasingly popular for deep learning, so we want to integrate it into DocArray.

- The project we propose is to add Jax as a backend for DocArray, alongside PyTorch and TensorFlow. The first part would involve rewriting and translating all of the computational backend functions of DocArray with the Jax framework. Then, we would battle-test the implementation against a real Jax use case, such as integrating DocArray with Jax support for model training and serving.

#### Expected outcomes

- We aim to provide JAX with the same level of support in DocArray as we do for pytorch, numpy, and tensorflow. The integration should be thoroughly tested and documented.

#### Desired skills

- Python proficiency is expected since the DocArray codebase is quite complete. Additionally, experience with the JAX framework and familiarity with the scientific Python ecosystem (e.g. NumPy, Torch, scikit-learn, etc.) is required.



### *🧬 Project idea X: Your own idea!*

Don't feel limited to the ideas above -- if you've got a cool project you want to work on, we'll probably be able to find you a mentor. We plan on approving as many projects as we possibly can.

If you have any ideas of your own, please feel free to send them to the mentors listed below. Your message should clearly state the project idea, the motivation behind it, the benefits it brings and a brief idea of how you wish to implement it. The project idea needs to be approved by the mentors to be officially accepted.



# 📝 How to apply

To apply for one of our projects, candidates need to create a proposal. If

- 👉 you want to work on a project idea listed below, discuss with mentors about how you plan on doing and submit a proposal.

- 👉 you want to work on your own project idea, get the project idea approved by one of the mentors via slack and submit a proposal.

**Submissions need to be made via email.** Please send your proposals to google-soc@jina.ai before the deadline as mentioned in the [timeline](https://developers.google.com/open-source/gsoc/timeline).

| name                                                       | email                           |
| :--------------------------------------------------------- | ------------------------------- |
| @[Felix Wang](https://github.com/numb3r3)                  | felix.wang@jina.ai              |
| @[Sami Jaghouar](https://github.com/samsja)                | sami.jaghouar@jina.ai           |
| @[Joan Martínez](https://github.com/JoanFM)                | joan.fontanals.martinez@jina.ai |
| @[Girish Chandrashekar](https://github.com/girishc13)      | girish.chandrashekar@jina.ai    |
| @[Johannes](https://github.com/JohannesMessner)            | johannes.messner@jina.ai        |
| @[Alaeddine Abdessalem](https://github.com/alaeddine-13)   | alaeddine.abdessalem@jina.ai    |
| @[Philip Vollet](https://www.linkedin.com/in/philipvollet) | philip.vollet@jina.ai           |

## How to create a project proposal?

We expect your application to be between 1000-1500 words. Your proposal should include all the necessary information listed below and should provide a detailed explanation of the problem you are trying to solve, the tools, data structures, algorithms, etc. that are necessary for you to complete the project successfully. At a minimum, your proposal should include the following information, as well as any other information you deem relevant:

```markdown
1. Your name, and email address

2. Title of Your Proposal

3. Abstract

Provide a brief summary of your proposal, including what it will contribute to the project and to Weaviate.

4. Detailed Description

Explain your idea in detail, including why it is innovative and what it will contribute to the project and to Jina AI. Include links to prototypes, bibliography, or other relevant sources.

5. Previous Work

Describe your academic studies, any previous work, internships, relevant work experience, or open source contributions (e.g. previous GSoC, PRs you made, etc.).

6. Relevant Skills

List the relevant skills that will help you to achieve the goal (programming languages, frameworks, etc.).

7. Commitment

Do you plan to have any other commitments during GSoC that may affect your work? Any vacations/holidays? Will you be available full time to work on your project? (Please refrain from applying if you cannot manage your time and cannot guarantee 100% commitment.)

```

Also, you must join our [Slack](https://jina.ai/slack/) and get in touch with the mentors before the submission deadline (one week ahead) so that they can help you draft an amazing application by reviewing it ahead of time.

The best way to demonstrate your capability is to submit a small patch/pull request before the project selection for an existing or new issue. We prefer candidates who are self-motivated, can work well with guidance from mentors, and have knowledge of Python, Machine Learning, and ANN Search experience.



## 🎓 What you will get

We strive to be helpful and welcoming to new open-source contributors. We hope that we can give participants a strong foundation of contributing to open-source Artificial Intelligence technologies and learn engineering best practices through their GSoC tenure with us.

All the mentors are from our own engineering team. They will mentor and review the mentee’s deliverables in detail, with timely communication and tracking of projects' progress, ensuring a very enriching internship experience.

As a student in Jina AI's GSoC program, you will have the opportunity to:

1. Gain hands-on experience with real-world projects and technologies in the field of search and AI.
2. Work with a mentor from the Jina AI who will support and guide you throughout the program.
3. Upon successful project completion, get invited as a speaker for our community events.
4. Regular feedback and help on your efforts, including blogposts, with quick responses from us
5. Develop your technical skills, including software development, machine learning, and open-source contributions.
6. Build your professional network and make connections with other students, developers, and experts in the field.
7. Receive a stipend from Google for your participation in the program.




## 🏁 Get started

- Please introduce yourself in #gsoc-introductions channel in our [Slack community](https://slack.jina.ai).
- Learn about Jina by reading the [documentation](https://docs.jina.ai/).
- Check out [Jina Hub](https://cloud.jina.ai/executors).



## 🤙 Communication

We have our own [Slack community](https://slack.jina.ai) for communication. If you have any questions, please don't hesitate to reach out to the mentors listed below on the #gsoc-support channel.



## 📝 How can I improve my chances of being accepted?

The best way to increase your chances of being accepted as a Jina AI GSoC student is to start contributing now. Read up on [Jina's contribution documentation](https://github.com/jina-ai/jina/blob/master/CONTRIBUTING.md) and make yourself known to the other contributors by your contributions (ideally, related to the area of your proposal). This way, when it comes time to evaluate student applications, you will be a recognized individual and more likely to receive the attention you need to develop a successful proposal.

We are looking for candidates who can demonstrate that they can work independently on a project. We are here to help, but we cannot monitor your progress every step of the way. Therefore, it is important to show us your motivation. Being active before the submission process is the best way to demonstrate this.
