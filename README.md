# Jina AI with GSoC 2022

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


## 🔎 Who are we?

<p align="center">
<b>
Welcome to the GSoC projects page of Jina AI! 
</b>
</p>

[Jina AI](https://jina.ai/) helps developers around the world build neural-search<sup><a href="https://docs.jina.ai/get-started/neural-search/">?</a></sup> powered apps in minutes. We focus on making AI usable for advanced human interactions and building a better ecosystem for developers. 

We are firm supporters of open source and have open sourced multiple projects, including:
 
- [**Jina**](https://github.com/jina-ai/jina): A cloud-native neural search framework to build state-of-the-art and scalable deep learning search applications in minutes.
- [**DocArray**](https://github.com/jina-ai/docarray): A library for nested, unstructured data in transit, including text, image, audio, video, 3D mesh, etc. It allows deep-learning engineers to efficiently process, embed, search, recommend, store, and transfer the data with a Pythonic API.
- [**Finetuner**](https://github.com/jina-ai/finetuner): Allows one to tune the weights of any deep neural network for better embeddings on search tasks.

We have also built an open source "app store" for sharing neural search components at [Jina Hub](https://hub.jina.ai/). These projects work in synergy to help developers build solutions for various problems, from image search to 3D model search, from semantic search to text-to-image search, from question-answering systems to outlier detection. 

We are always enthusiastic about GSoC and we believe this experience will help us empower more users, improve open source and overall, improve developer experience. 

Listed below are project ideas which work towards the idea of using AI for good. Each project comes with a lot of learning and every participant will be guided thoroughly by our dedicated mentors. Please feel free to come up with your own ideas too!

We invite everyone to participate in GSoC 2022 with Jina AI!

## 🤙 Communication

We have our own [Slack community](https://slack.jina.ai) for communication. Please feel free to contact the mentors listed below on the #gsoc-support channel with your queries. 

## 📝 How to apply

To apply for one of our projects, candidates need to create a proposal. If:

- 👉 Option 1: You want to work on your own project idea. The first step would be to get the project idea approved by the mentors by discussing with them over slack. Next, a proposal should be made for that project.

- 👉 Option 2: You want to work on a project idea listed below. Discuss with mentors about the architechture and how you plan on doing it. Next, create a proposal and submit it.

Any proposal submitted should follow [this](https://docs.google.com/document/d/1vPWIxH-o8KBIbL1FPZai5EBLWWnDy2K6FXc2HV3D1q8/edit?usp=sharing) proposal template. Submissions need to be made via email. Please send your proposals to google-soc@jina.ai
 before the deadline as mentioned in the [program timeline](https://developers.google.com/open-source/gsoc/timeline).

For questions about how to create a good proposal, please refer to the [proposal guide](https://google.github.io/gsocguides/student/writing-a-proposal) from GSoC. 



## 🎓 What you will get

We strive to be helpful and welcoming to new open-source contributors. We hope that we can give participants a strong foundation of contributing to open-source artificial intelligence and neural search technologies and learn engineering best practices through their GSoC tenure with us.

All the mentors are from our own engineering team. They will mentor and review the mentee’s deliverables in detail, with timely communication and tracking of projects' progress, ensuring a very enriching internship experience.

You can expect to:

- Learn how to work in an open-source project.
- Learn how to build a neural search system with state-of-the-art neural networks.
- Learn best practices in writing code.
- Get credits from GSoC.
- Get awesome swag.
- Upon successful project completion, get invited as a speaker for our community events.
- Dive deeply into AI and ML, learn new concepts and develop apps that serve a purpose.

## 💡 Project ideas


| Title                           | Involves      | Skills needed              | Mentors |
|---------------------------------|---------------|----------------------------|------------|
| Accurate landmark search system | Jina, DocArray, Finetuner | Python, Deep learning | Bo(dot)Wang(at)jina(dot)ai, Jie(dot)Fu(at)jina(dot)ai|
| Jina AI playground              | Jina, DocArray | JavaScript, Python, HTML, CSS |Yanlong(dot)Wang(at)jina(dot)ai |
| Data visualisation in the browser using DocArray | DocArray | JavaScript, Python, HTML, CSS|Bo(dot)Wang(at)jina(dot)ai|
| 3D search application - Build and Finetune| Jina, DocArray, Finetuner | Python, Deep learning | Felix(dot)Wang(at)jina(dot)ai |

### *Project idea 1: Accurate landmark search system*

| info | details |
| --- | --- |
| Involves | Jina, DocArray, Finetuner |
| Skills needed | Python, Deep Learning |
| Project size | 350 hours |
| Mentors | Bo(dot)Wang(at)jina(dot)ai , Jie(dot)Fu(at)jina(dot)ai |


Landmark retrieval is a hot topic in both academic research and industrial applications. We realise the importance of landmark retrieval rising up again post-COVID. As tourist places open again, we can expect an increase in the number of queries tackled related to landmark search. 

The project aims to create an image-to-image search system, wherein we input an image containing a tourist landmark and expect to retrieve photos of the same landmark sites but taken at different times of the year. However, most of the work thus far has been to optimise accuracy, rather than "usefulness", of the search results. 

This application expects you to train a machine learning model and create a faceted search system. The model will be trained to recognize not only similar images, but also rank them on the basis of months in a year. The faceted search will enable users to filter search results and manipulate searches according to their use cases.

For instance, given a photo of the Great Wall of China, the system renders Great Wall photos and re-ranks them by different seasonal images (e.g. summer scene, winter scene etc..). 

Finally, the trained model will be put to use in building a tourist landmark search system with Jina. An additional task would be to showcase the tag of "safe to visit" or "unsafe to visit" in the pandemic.
 

### *Project idea 2: Jina AI Playground*

| info | details |
| --- | --- |
| Involves | Jina, DocArray |
| Skills needed | JavaScript, Python, HTML, CSS |
| Project size | 350 hours |
| Mentors | Yanlong(dot)Wang(at)jina(dot)ai |


Jina’s documentation contains a lot of examples ranging from normal vector search to multimodal searches. External developers wanting to explore neural search and see how code correlates to output might want to experience some examples hands-on. 

We are already in the process of building a helpful community where developers can get their questions answered easily but we get a lot of questions about runtime errors because of varied environments. To mitigate this and show the users how Jina works and produces results, we propose to create an integrated playground IDE for Jina where code can be seen in action.

This project will combine Jina’s backend with external frontend frameworks to create a playground where developers will be able to see the source code and the output it renders. 


### *Project idea 3: Data visualisation in the browser using DocArray*

| info | details |
| --- | --- |
| Involves | DocArray |
| Skills needed | JavaScript, Python, HTML, CSS |
| Project size | 350 hours |
| Mentors | Bo(dot)Wang(at)jina(dot)ai |

Data visualisation helps lay a better foundation for data interpretation. Data engineers require data visualisation the most and efforts have been made in making data visualisation easier and faster. 

We have an in-built feature of DocArray that allows the users to visualise their data. Adding to this, users can also manipulate their data in any way they want. The main motivation behind this project is to showcase DocArray’s visualisation capabilities quickly and give users a hands-on experience.

We want to make use of front-end frameworks to bring DocArray’s capabilities in the browser. The idea is to implement DocArray’s visualisation feature in the browser so that with just a few clicks , users are able to see and interpret their data. The backend would be based on DocArray and solely written in Python while for the front-end, any framework can be used.

Additional functionalities 350 hourswould be welcomed but they are not a necessity. These additional functionalities will be catering to implementing different DocArray functions in the browser like creating a DocArray, matching nearest neighbours, embedding, etc.
An example of data visualisation can be seen [here](https://docarray.jina.ai/_images/embedding-projector-empty.gif).



### *Project idea 4: 3D search application - Build and Finetune*

| info | details |
| --- | --- |
| Involves | Jina, DocArray, Finetuner |
| Skills needed | Python, Deep Learning |
| Project size | 350 hours |
| Mentors | Felix(dot)Wang(at)jina(dot)ai |


A 3D mesh is the structural build of a 3D model consisting of polygons. The data type is used in a variety of places but it is not always easy to create a search system catering to only 3D mesh data types. For this project, we have narrowed down our use case to 3D printing.

The project will be an open source search app where users will be able to find 3D models similar to the ones they input. 

The features for the project will be built in 3 steps:

- Support: The user enters the 3D file as a query. The matching here becomes a simple search
- Feature (required): Image as a query. The challenge would be to take a 2D input and render 3D models as output.
- Feature (optional): Text as a query. The challenge here will be to take the input as text and render 3D models related to it.


If you want to know more about how to handle 3D mesh, look into the Jina documentation on [3D mesh](https://docarray.jina.ai/datatypes/mesh/).

### *Your own idea!*

If you have any ideas of your own, please feel free to send them to the mentors listed below. Your message should clearly state the project idea, the motivation behind it, the benefits it brings and a brief idea of how you wish to implement it. The project idea needs to be approved by the mentors to be officially accepted.

### Get started

- Please introduce yourself in #gsoc-introductions channel in our [Slack community](https://slack.jina.ai) and 
- Learn about Jina by reading the [documentation](https://docs.jina.ai/) and [Learning Portal](https://learn.jina.ai).
- Check out [Jina Hub](https://hub.jina.ai). - 

