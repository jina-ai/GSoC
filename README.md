

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

##🔎 Who are we

[Jina AI](jina.ai) is an open source software company behind couples of open-source projets, including:

- [Jina](https://github.com/jina-ai/jina): Data type agnostic Python library for effortless processing and manipulation of data. A single data structure for all kinds of data.

- [Docarray](https://github.com/jina-ai/docarray): A cloud-native neural search framework to build SOTA and scalable deep learning search applications in minutes.

- [Finetuner](https://github.com/jina-ai/finetuner): Finetune any deep neural network for better embedding on neural search tasks

## Communication:

We have our own [slack channel](https://slack.jina.ai) for communication. Please feel free to contact the mentors listed below with your doubts/queries. 

## 📝 How to Apply

## What You Will Get

We strive to be helpful and welcoming to new open source contributors. We hope that we can help give the participants a strong foundation of contributing to open-source artificial intelligence and neural search and learn best engineering practices through their GSoC tenure with us.

All the mentors are from our own engineering team. They will mentor and review the mentee’s deliverables in detail, with timely communication and tracking of projects’ progress, ensuring a very enriching internship experience.

You can expect to

- learn how to work in an open source project.
- learn how to build a neural search system with the SOTA models.
- learn best practices in writing codes.
- get credits from GSoC.
- get awesome SWAGS.

### *Project idea 1- Accurate landmark search system *

| Involves | Jina |
| --- | --- |
| Skills needed | Python, Javascript, Unit Testing, Architecture design, Machine Learning|
| Project size | Large |
| Difficulty | Medium |
| Mentors | |

#### Project description

### *Project 1: Context-Aware Landmark Search*
 
Landmark retrieval is a hot topic in both academic resarch and industrial applications. Given a Image-to-Image search system, we input an image contains a tourist Landmark and expect to retrieve photos of the same Landmark sites. However, most of the job has been done to optimize the accuracy of the search results, ratther than the "usefulness" of the search results. This application expect you to train a machine learning model care beyond accuracy. For instance, given a photo of the Great Wall, you get Great Wall photos and re-rank them by different seasonal images (e.g. summer scene, snow scene etc..). Finally, you incorporate your model and build a tourist Landmark search system with Jina.

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

### *Project X: Interested in proposing a new project idea altogether?*

A good starting point would be introducing yourself in the `#introductions` channel on our slack and then, learning about [Jina](https://docs.jina.ai/). If you are already familiar with Jina, please look into working with [3D mesh](https://docarray.jina.ai/datatypes/mesh/) with Jina.

### *Your own idea!*

- Join our [Slack community](https://slack.jina.ai) to chat to our engineers about your use cases, questions, and
  support queries.
- Join our [Engineering All Hands](https://youtube.com/playlist?list=PL3UBBWOUVhFYRUa_gpYYKBqEAkO4sxmne) meet-up to
  discuss your use case and learn Jina's new features.
    - **When?** The second Tuesday of every month
    - **Where?**
      Zoom ([see our public calendar](https://calendar.google.com/calendar/embed?src=c_1t5ogfp2d45v8fit981j08mcm4%40group.calendar.google.com&ctz=Europe%2FBerlin)/[.ical](https://calendar.google.com/calendar/ical/c_1t5ogfp2d45v8fit981j08mcm4%40group.calendar.google.com/public/basic.ics)/[Meetup
      group](https://www.meetup.com/jina-community-meetup/))
      and [live stream on YouTube](https://youtube.com/c/jina-ai)
- Subscribe to the latest video tutorials on our [YouTube channel](https://youtube.com/c/jina-ai)

