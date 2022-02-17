
# Jina AI with GSoC 2022



<p align="center">
<img src="https://jina.ai/assets/images/logo.svg" alt="GSoC banner" width="20%" >
</p>
<p align="center">
<img src="https://summerofcode.withgoogle.com/assets/media/logo.svg" alt="GSoC banner" width="60%" >
</p>

<!--<p align="center"><b>
Project Proposals Idea List Page for Google Summer of Code 2021 with Jina</b>
</p>-->
<!--<p align="center">
<img src="https://github.com/jina-ai/jina/blob/master/.github/logo-only.gif?raw=true" alt="Jina banner" width="200px">
</p>-->

## 🔎 Who are we

Welcome to the projects page of Jina AI. Jina AI works towards helping developers around the world build neural-search powered apps in minutes. We focus on making AI usable for advanced human interactions and making a better ecosystem for developers. 

Being firm supporters of open source, we have open sourced our 3 projects : 
- [Jina](https://github.com/jina-ai/jina): A cloud-native neural search framework to build SOTA and scalable deep learning search applications in minutes.
- [Finetuner](https://github.com/jina-ai/finetuner): Finetune any deep neural network for better embedding on neural search tasks
- [DocArray](https://github.com/jina-ai/docarray) : Data type agnostic Python library for effortless processing and manipulation of data. A single data structure for all kinds of data.
- [Jina Hub](https://hub.jina.ai/): An open source marketplace for Executors.

These 3 projects work in synergy to produce the most accurate neural search systems there are. 
This year we are enthusiastic about GSoC and we believe this experience will help us empower more users, imoprive open source and overall, improve the developer experience. 

Listed below are 7 medium-advanced project ideas which work towards the idea of using AI for good. Each project comes with a lot of learning and every participant will be guided thoroughly by our dedicated mentors. Please feel free to come up with your own ideas too.

We invite everyone to participate in GSoC 2022 with Jina AI!

## Communication:

We have our own [slack channel](https://slack.jina.ai) for communication. Please feel free to contact the mentors listed below with your doubts/queries. 

## 📝 How to Apply

To apply to one of our projects, the candidates need to create a proposal and we have put together a proposal template so it becomes easier for participants to prepare a proposal. For questions about how to create a proposal, please refer to the proposal guide listed [here](https://google.github.io/gsocguides/student/writing-a-proposal) by GSoC. 

The submissions need to be made via mail. Please send your proposals to jyoti.bisht@jina.ai before the deadlines as mentioned in the program timeline.

## What You Will Get

We strive to be helpful and welcoming to new open source contributors. We hope that we can help give the participants a strong foundation of contributing to open-source artificial intelligence and neural search and learn best engineering practices through their GSoC tenure with us.

All the mentors are from our own engineering team. They will mentor and review the mentee’s deliverables in detail, with timely communication and tracking of projects’ progress, ensuring a very enriching internship experience.

You can expect to

- learn how to work in an open source project.
- learn how to build a neural search system with the SOTA models.
- learn best practices in writing codes.
- get credits from GSoC.
- get awesome SWAGS.
- upon successful project completion, get invited as a speaker for our community events.
- deep dive into AI and ML, learn new concepts and develop apps that serve a purpose.

## 💡 Project Ideas

### *Project idea 1- Accurate landmark search system*

| Involves | Jina |
| --- | --- |
| Skills needed | Python, Javascript, Unit Testing, Architecture design, Machine Learning|
| Project size | Large |
| Difficulty | Medium |
| Mentors | |

#### Project description

Landmark retrieval is a hot topic in both academic research and industrial applications. We realise the importance of landmark retrieval rising up again post COVID. As the tourist places open again, we can expect an increase in the number of queries tackled related to landmark search. 

The project aims to create an Image-to-Image search system, wherein we input an image containing a tourist landmark and expect to retrieve photos of the same landmark sites but taken at different times in a year. However, most of the job has been done to optimise the accuracy of the search results, rather than the "usefulness" of the search results. 

This application expects you to train a machine learning model and create a faceted search system. The model will be trained to recognize not only the similar images but also, rank them on the basis of months in a year. The faceted search will enable users to apply for filters and manipulate search according to their use cases.

For instance, given a photo of the Great Wall of China, the system renders Great Wall photos and re-ranks them by different seasonal images (e.g. summer scene, snow scene etc..). 

Finally, the trained model will be put to use in building a tourist Landmark search system with Jina. An additional task would be to showcase the tag of “safe to visit” or “unsafe to visit” in the pandemic.
 
#### Getting started:
Please introduce yourself in #introductions channel in our slack channel and learn about Jina by reading the [documentation](https://docs.jina.ai/). 

#### 🎯 Desired Outcomes


### *Project idea 2- Jina AI playground*

| Involves | Jina |
| --- | --- |
| Skills needed | Javascript, Python, Compiler design, Testing, HTML, CSS |
| Project size | Large |
| Difficulty | Hard |
| Mentors | |

#### Project description

Jina’s documentation contains a lot of examples ranging from normal vector search to multimodal searches. External developers wanting to explore neural search and wanting to see how the code correlates to the output, might want to experience some examples hands-on. 

We are already in the process of building a helpful community where developers can find their doubts cleared easily but we get a lot of questions about runtime errors because of varied environments. To mitigate this and show the users how Jina works and produces results, we propose to create an IDE integrated playground for Jina where the dummy code can be seen in action.

This project will combine Jina’s backend and external frontend frameworks to create a playground where developers will be able to see the source code and the output it renders. 

#### Getting started:
Please introduce yourself in `#introductions` channel in our slack channel and learn about Jina by reading the [documentation](https://docs.jina.ai/). 


### *Project idea 3- Data visualisation in the browser using DocArray*

| Involves | Jina |
| --- | --- |
| Skills needed | Javascript, Python, Compiler design, Testing, HTML, CSS |
| Project size | Large |
| Difficulty | Hard |
| Mentors | |

#### Project description

Data visualisation helps lay a better foundation for data interpretation. Data engineers require data visualisation the most and efforts have been made in making data visualisation easier and faster. 

We have an in-built feature of DocArray that allows the users to visualise their data. Adding to this, users can also manipulate their data in any way they want. The main motivation behind this project is to showcase DocArray’s visualisation capabilities quickly and give users a hands-on experience.

We want to make use of front-end frameworks to bring DocArray’s capabilities in the browser. The idea is to implement DocArray’s visualisation feature in the browser so that with just a few clicks , users are able to see and interpret their data. The backend would be based on DocArray and solely written in Python while for the front-end, any framework can be used.

Additional functionalities would be welcomed but they are not a necessity. These additional functionalities will be catering to implementing different DocArray functions in the browser like creating a DocArray, matching nearest neighbours, embedding, etc.
An example of data visualisation can be seen [here](https://docarray.jina.ai/_images/embedding-projector-empty.gif).

#### Getting started:
Please introduce yourself in `#introductions` channel in our slack channel and learn about DocArray by reading the [documentation](https://docarray.jina.ai/). 


### *Project idea 4- Build Hub Executors for Jina Hub*

| Involves | Jina , Jina Hub|
| --- | --- |
| Skills needed | Python, Unit Testing, ConvNet |
| Project size | Large |
| Difficulty | Hard |
| Mentors | |

#### Project description

Jina Hub is an open source marketplace for [Executors](https://docs.jina.ai/fundamentals/executor/). As AI gets smarter, researchers have been trying to make accurate AI models and better search engines. The ability of AI to recognize data is extending and now spans over image data too. 
Specifically, with this project we are focusing on improving the user experience for search engines that use image classification. [This](https://arxiv.org/abs/2201.03545) brilliant research paper explains in depth how visual transformers are a good aid in image classification but they face problems in object detection and semantic segmentation. 

The result of this paper was the birth of ConvNeXt which scales better than Transformers in terms of accuracy and stability. Since this innovation is an improved ConvNet and will help AI researchers around the world, we want to make ConvNeXt-enabled Executor possible for Jina so that the task of image classification becomes easier, more accurate and more user friendly. 

This project is well suited for people who are interested in AI and have experience working with neural networks. The project involves a good amount of researching and reading of research papers based on ConvNet models. Jina Hub being purely open source, this will pave the way for developers to use the power of ConvNeXt for building accurate image classification systems.


#### Getting started:

Please introduce yourself in `#introductions` channel in our slack and learn about [Jina](https://docs.jina.ai/) and [Jina Hub](https://hub.jina.ai/). The project involves creation of executors, so try to make yourself familiar with Executors in depth.


### *Project idea 5 - 3D search application - Build and Finetune*

| Involves | Finetuner |
| --- | --- |
| Skills needed | Python, Unit Testing, ConvNet |
| Project size | Large |
| Difficulty | Hard |
| Mentors | |

#### Project description

3D mesh is a structural build of a 3D model consisting of polygons. The data type is used in a variety of places but it is not always easy to create a search system catering to only the 3D mesh data types. For this project, we have narrowed down our use case to a 3D printer. 

The project will be an open source search app where users will be able to find 3D models similar to the ones they input. 

The features for the project will be built in 3 steps:
- Support: The user enters the 3D file as a query. The matching here becomes simple search
- Feature (required): Image as a query. The challenge would be to take a 2D input and render 3d models as output.
- Feature (optional) : Text as a query. The challenge here will be to take the input as text and render 3d models related to it.


#### Getting started:

A good starting point would be introducing yourself in the `#introductions` channel on our slack and then, learning about [Jina](https://docs.jina.ai/). If you are already familiar with Jina, please look into working with [3D mesh](https://docarray.jina.ai/datatypes/mesh/) with Jina.

### *Your own idea!*

If you have any idea of your own, please feel free to send it to the mentors listed below. Your message should clearly state the project idea, the motivation behind it, the benefits it brings and a brief idea of how you wish to implement it. The project idea needs to be approved by the mentors to be officially accepted.

