# Jina AI with GSoC 2022

<p align="center">
<img src="https://jina.ai/assets/images/logo.svg" alt="GSoC banner" width="20%" >
</p>
<p align="center">
<b>
X
</b>
<p>
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

Listed below are five medium-to-advanced project ideas which work towards the idea of using AI for good. Each project comes with a lot of learning and every participant will be guided thoroughly by our dedicated mentors. Please feel free to come up with your own ideas too!

We invite everyone to participate in GSoC 2022 with Jina AI!

## 🤙 Communication

We have our own [Slack community](https://slack.jina.ai) for communication. Please feel free to contact the mentors listed below on the #gsoc-support channel with your queries. 

## 📝 How to apply

To apply for one of our projects, candidates need to create a proposal. We have put together a proposal template to make this easier. For questions about how to create a proposal, please refer to the [proposal guide](https://google.github.io/gsocguides/student/writing-a-proposal) from GSoC. 

Submissions need to be made via email. Please send your proposals to jyoti.bisht@jina.ai before the deadlines as mentioned in the program timeline.

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

| Title                                            | Involves                  | Skills needed                                  | Difficulty | Mentors |
|--------------------------------------------------|---------------------------|------------------------------------------------|------------|---------|
| Accurate landmark search system                  | Jina, Finetuner           | Python, Machine Learning                       | Medium     | Bo, Jie |
| Jina AI playground                               | Jina, DocArray            | JavaScript, Python| Hard       |         |
| Data visualisation in the browser using DocArray | DocArray                  | JavaScript, Python| Hard       |         |
| Build Hub Executors for Jina Hub                 | Jina, DocArray            | Python, Deep learning                          | Hard       |         |
| 3D search application - Build and Finetune       | Jina, DocArray, Finetuner | Python, Deep learning                          | Hard       |         |

### *Project idea 1: Accurate landmark search system*

| Involves | Jina |
| --- | --- |
| Skills needed | Python, JavaScript, Unit Testing, Architecture design, Machine Learning|
| Project size | Large |
| Difficulty | Medium |
| Mentors | |


Landmark retrieval is a hot topic in both academic research and industrial applications. We realise the importance of landmark retrieval rising up again post-COVID. As tourist places open again, we can expect an increase in the number of queries tackled related to landmark search. 

The project aims to create an image-to-image search system, wherein we input an image containing a tourist landmark and expect to retrieve photos of the same landmark sites but taken at different times of the year. However, most of the work thus far has been to optimise accuracy, rather than "usefulness", of the search results. 

This application expects you to train a machine learning model and create a faceted search system. The model will be trained to recognize not only similar images, but also rank them on the basis of months in a year. The faceted search will enable users to filter search results and manipulate searches according to their use cases.

For instance, given a photo of the Great Wall of China, the system renders Great Wall photos and re-ranks them by different seasonal images (e.g. summer scene, winter scene etc..). 

Finally, the trained model will be put to use in building a tourist landmark search system with Jina. An additional task would be to showcase the tag of "safe to visit" or "unsafe to visit" in the pandemic.
 


#### 🎯 Desired outcomes


### *Project idea 2: Jina AI Playground*

| Involves | Jina |
| --- | --- |
| Skills needed | JavaScript, Python, Compiler design, Testing, HTML, CSS |
| Project size | Large |
| Difficulty | Hard |
| Mentors | |

#### Project description

Jina’s documentation contains a lot of examples ranging from normal vector search to multimodal searches. External developers wanting to explore neural search and see how code correlates to output might want to experience some examples hands-on. 

We are already in the process of building a helpful community where developers can get their questions answered easily but we get a lot of questions about runtime errors because of varied environments. To mitigate this and show the users how Jina works and produces results, we propose to create an integrated playground IDE for Jina where code can be seen in action.

This project will combine Jina’s backend with external frontend frameworks to create a playground where developers will be able to see the source code and the output it renders. 

#### Get started:

Please introduce yourself in #gsoc-introductions channel in our [Slack community](https://slack.jina.ai) and learn about Jina by reading the [documentation](https://docs.jina.ai/) and [Learning Portal](https://learn.jina.ai). 

### *Project idea 3: Data visualisation in the browser using DocArray*

| Involves | Jina |
| --- | --- |
| Skills needed | JavaScript, Python, Compiler design, Testing, HTML, CSS |
| Project size | Large |
| Difficulty | Hard |
| Mentors | |

#### Project description

Data visualisation helps lay a better foundation for data interpretation. Data engineers require data visualisation the most and efforts have been made in making data visualisation easier and faster. 

We have an in-built feature of DocArray that allows the users to visualise their data. Adding to this, users can also manipulate their data in any way they want. The main motivation behind this project is to showcase DocArray’s visualisation capabilities quickly and give users a hands-on experience.

We want to make use of front-end frameworks to bring DocArray’s capabilities in the browser. The idea is to implement DocArray’s visualisation feature in the browser so that with just a few clicks , users are able to see and interpret their data. The backend would be based on DocArray and solely written in Python while for the front-end, any framework can be used.

Additional functionalities would be welcomed but they are not a necessity. These additional functionalities will be catering to implementing different DocArray functions in the browser like creating a DocArray, matching nearest neighbours, embedding, etc.
An example of data visualisation can be seen [here](https://docarray.jina.ai/_images/embedding-projector-empty.gif).

#### Get started:
Please introduce yourself in #gsoc-introductions channel in our [Slack community](https://slack.jina.ai) and learn about Jina by reading the [documentation](https://docs.jina.ai/) and [Learning Portal](https://learn.jina.ai). 


### *Project idea 4: Build Hub Executors for Jina Hub*

| Involves | Jina, DocArray, Jina Hub|
| --- | --- |
| Skills needed | Python, Deep Learning |
| Project Size | 175 hours |
| Mentors | |


Jina Hub is an open source "app store" for [neural search building blocks](https://docs.jina.ai/fundamentals/executor/). As AI gets smarter, researchers have been trying to make accurate AI models and better search engines. The ability of AI to recognize data is extending and now spans over image data too. 
Specifically, with this project we are focusing on improving the user experience for search engines that use image classification. [This](https://arxiv.org/abs/2201.03545) brilliant research paper explains in depth how visual transformers are a good aid in image classification but face problems in object detection and semantic segmentation. 

The result of this paper was the birth of ConvNeXt which scales better than Transformers in accuracy and stability. Since this innovation is an improved ConvNeXt and will help AI researchers around the world, we want to make a ConvNeXt-enabled Executor possible for Jina so that image classification becomes easier, more accurate and more user-friendly. 

This project is well suited for people who are interested in AI and have experience working with neural networks. The project involves a good amount of research and reading research papers based on ConvNet models. [Jina Hub](https://hub.jina.ai) being purely open source, this will pave the way for developers to use the power of ConvNeXt to build accurate image classification systems.

If you want to know more, we recommend reading up on [Executors and how they work](https://docs.jina.ai/fundamentals/executor/). 




### *Project idea 5: 3D search application - Build and Finetune*

| Involves | Jina, DocArray, Finetuner |
| --- | --- |
| Skills needed | Python, Deep Learning |
| Difficulty | Medium |
| Mentors | |


A 3D mesh is the structural build of a 3D model consisting of polygons. The data type is used in a variety of places but it is not always easy to create a search system catering to only 3D mesh data types. For this project, we have narrowed down our use case to 3D printing.

The project will be an open source search app where users will be able to find 3D models similar to the ones they input. 

The features for the project will be built in 3 steps:

- Support: The user enters the 3D file as a query. The matching here becomes a simple search
- Feature (required): Image as a query. The challenge would be to take a 2D input and render 3D models as output.
- Feature (optional) : Text as a query. The challenge here will be to take the input as text and render 3D models related to it.


If you want to know more about how to handle 3D mesh, look into the Jina documentation on [3D mesh](https://docarray.jina.ai/datatypes/mesh/).

### *Your own idea!*

If you have any ideas of your own, please feel free to send them to the mentors listed below. Your message should clearly state the project idea, the motivation behind it, the benefits it brings and a brief idea of how you wish to implement it. The project idea needs to be approved by the mentors to be officially accepted.

### Get started

- Please introduce yourself in #gsoc-introductions channel in our [Slack community](https://slack.jina.ai) and 
- Learn about Jina by reading the [documentation](https://docs.jina.ai/) and [Learning Portal](https://learn.jina.ai).
- Check out [Jina Hub](https://hub.jina.ai). - 

