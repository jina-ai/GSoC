<p align="center">
<img src="https://github.com/jina-ai/GSoC/blob/main/images/gsoc.png?raw=true" alt="Jina GSoC banner" width="300px" height="300px">
</p>

# GSoC 2021 with Jina AI
<p align="center">
Project Proposals Idea List Page for Google Summer of Code 2021 with Jina
</p>
<p align="center">
<img src="https://github.com/jina-ai/jina/blob/master/.github/logo-only.gif?raw=true" alt="Jina banner" width="200px">
</p>

## About us

[Jina](get.jina.ai) is a leading neural search open source project (2.3K+ GitHub stars and 360+ forks in less than a year). The project is maintained by a full-time engineering team at Jina AI, a company fully committed to open source. 

We, the Jina community, strive to be helpful and welcoming to new open source contributors. We hope that we can help give students a strong foundation of contributing to open-source artificial intelligence and neural search and learn best engineering practices through their GSoC tenure with us.

All the mentors are from our own engineering team. They will mentor and review the mentee’s deliverables in detail, with timely communication and tracking of projects’ progress, ensuring a very enriching internship experience.

## This summer

Jina has a lot of challenging and exciting projects ongoing this summer.Until today, we've introduced cross- and multi-modal search and have 90+ first class AI models implemented as Jina Executors in production and available as Docker images.

This year, we aim to introduce more features e.g. transfer learning, graph learning, reinforcement learning and fine tuning, and there are extensive designing and engineering work for this during this year's GSoC. 

Also, we aim to introduce and adapt even more state-of-the-art AI models in Jina Hub with the help of GSoC program. 

We look forward to contributions from our community, engineering team and interns together to successfully achieve our goals this summer.

## Our repositories

- [Jina Core](https://github.com/jina-ai/jina)
- [Jina Hub](https://github.com/jina-ai/jina-hub)
- [Jina Box](https://github.com/jina-ai/jinabox.js)
- [Jina Dashboard](https://github.com/jina-ai/dashboard)
- [Jina Examples](https://github.com/jina-ai/examples)
- [Documentation](https://github.com/jina-ai/docs)


## GSoC 2021 Idea List:

### *Project 1: Port State of the Art AI models to Jina Hub*
 
#### Abstract
 
Jina Hub hosts state of the art AI models in the form of Executors for various stages of the neural search pipeline - segmenting, crafting, encoding, indexing and ranking data. This project will focus on adapting new state-of-the-art AI models to neural search and making them publicly available for the community via Jina Hub
Contributing to [Jina Hub](https://github.com/jina-ai/jina-hub)

 
| **Intensity** | **Priority** | **Involves**                            | **Mentors**                                                                                              |
|---------------|--------------|-----------------------------------------|----------------------------------------------------------------------------------------------------------|
| Moderate      | High         | Implement new Jina Hub Models. | [Rutuja Surve](https://github.com/rutujasurve94), Mail: rutuja(dot)surve(at)jina(dot)ai|
 
#### Technical Details
 
[Jina Hub repository](https://github.com/jina-ai/jina-hub)
is the code base hosting Jina Executors.
[Jina AI Docker Hub](https://hub.docker.com/u/jinaai) is the go to platform for the existing hub executors like BigTransferEncoder, etc.
 
#### Helpful Experience
 
- Python programming and experience with Docker
- Ability to read scientific publications
- Knowledge of Numpy
- Basic knowledge of popular deep learning frameworks like Tensorflow, Pytorch, Keras, etc.
 
#### First Steps
 
- Study the `jina-hub` repository, understand the existing Executors
- Propose an AI model of any executor kind - indexer, ranker, crafter, segmenter, encoder.
- Actively get involved with the GitHub issues in the repo, picking up good beginner tasks, getting in touch with the mentors.
- Submit patches with clean unit test cases and review them from the jina-engineering team.
- Discuss your proposal with the mentors.
- Join our slack channel or mail our mentors to get in touch with them for more information



### *Project 2: Build an example for an application of your choice*
 
#### Abstract
 
Write a neural search pipeline to solve a real-world problem. Use any Kaggle or other open source datasets. Include well-written documentation and a blog post (and/or Demo video) to create outreach for yourself and Jina.
 
 
| **Intensity** | **Priority** | **Involves**                            | **Mentors**                                                                                              |
|---------------|--------------|-----------------------------------------|----------------------------------------------------------------------------------------------------------|
| Moderate      | High         | Build an example using Jina | [Rutuja Surve](https://github.com/rutujasurve94) Mail: rutuja(dot)surve(at)jina(dot)ai, [Susana Guzman](https://github.com/catstark) Mail: susana(dot)guzman(at)jina(dot)ai|
 
#### Technical Details
 
[Jina Examples repository](https://github.com/jina-ai/examples)
is the code base hosting Jina Examples like southpark-search, pokedex-search.
[Jina AI Docker Hub](https://hub.docker.com/u/jinaai) is the go to platform for the existing hub executors like BigTransferEncoder, etc.
 
#### Helpful Experience
 
- Python programming and experience with Docker
- Ability to extend SOTA AI models using deep learning frameworks
- Knowledge of Numpy
- Basic knowledge of popular deep learning frameworks like Tensorflow, Pytorch, Keras, etc.
 
#### First Steps
 
- Study the `examples` repository, understand the existing examples
- Propose an application of your choice for an interesting use-cases
- Actively get involved with the GitHub issues in Jina repo, picking up good beginner tasks, getting in touch with the mentors.
- Submit patches with clean unit test cases and review them from the jina-engineering team.
- Discuss your proposal with the mentors.
- Join our slack channel or mail our mentors to get in touch with them for more information



### *Project 3: Improve docstring coverage for Jina*

- Contribution towards Jina’s code and [API Reference Documentation](https://github.com/jina-ai/docs), making the code highly readable. 
- Scope for refactoring as per best practices.


| **Intensity** | **Priority** | **Involves**                            | **Mentors**                                                                                              |
|---------------|--------------|-----------------------------------------|----------------------------------------------------------------------------------------------------------|
| Moderate      | Medium         | Implement new Jina Hub Models. | Yongxuan Zhang: yongxuan(dot)zhang(at)jina(dot)ai, Susana Guzman: susana(dot)guzman(at)jina(dot)ai, Rutuja Surve: rutuja(dot)surve(at)jina(dot)ai |
 


#### First Steps
 
- Study the [jina](https://github.com/jina-ai/jina) and [jina-hub](https://github.com/jina-ai/jina-hub) repository, understand the codebase
- Actively get involved with the GitHub issues with documentation tag in Jina repo, picking up good beginner tasks, getting in touch with the mentors.
- Submit patches with clean unit test cases and review them from the jina-engineering team.
- Discuss your proposal with the mentors.
- Join our slack channel or mail our mentors to get in touch with them for more information



### *Project 4:  Enhancements for JinaBox, Jina Console and Dashboard*

- Work on exciting frontend features for enhancing UI and UX
- Contribute to [Jina Hub](https://github.com/jina-ai/jina-hub) or [Jina Box](https://github.com/jina-ai/jinabox.js)

| **Intensity** | **Priority** | **Involves**                            | **Mentors**                                                                                              |
|---------------|--------------|-----------------------------------------|----------------------------------------------------------------------------------------------------------|
| Moderate      | Medium         | Implement new features for Jina Box, Console. | Sergiy Chemodanov: sergiy(at)jina(dot)ai, Bastin Jafari: bastin(dot)jafari(at)jina(dot)ai|


#### First Steps
 
- Study the [`jinabox`](https://github.com/jina-ai/jinabox.js) and [`dashboard`](https://github.com/jina-ai/dashboard) repository, understand the codebase
- Actively get involved with the GitHub issues in these repositories.
- Join our slack channel or mail our mentors to get in touch with them for more information



### *Project X: Interested in proposing a new project idea altogether?*

We are always excited to hear from the community about potential projects and features Jina could host. If you are excited about any idea and would like to
propose it as a GSoC project, get in touch with our mentors and we'd be very happy to be inclusive.


## Contributing

Follow the guidelines below while submitting your first patch to Jina:

- [Contributing guidelines](https://github.com/jina-ai/jina/blob/master/CONTRIBUTING.md)
- [Release cycles and development stages](https://github.com/jina-ai/jina/blob/master/RELEASE.md)

## Get in touch with the Jina Community!

- [Code of conduct](https://github.com/jina-ai/jina/blob/master/.github/CODE_OF_CONDUCT.md) - play nicely with the Jina community
- [Slack workspace](https://slack.jina.ai) - join #general on our Slack to meet the team and ask questions
- [YouTube channel](https://youtube.com/c/jina-ai) - subscribe to the latest video tutorials, release demos, webinars and presentations.
- [LinkedIn](https://www.linkedin.com/company/jinaai/) - get to know Jina AI as a company and find job opportunities
- [![Twitter Follow](https://img.shields.io/twitter/follow/JinaAI_?label=Follow%20%40JinaAI_&style=social)](https://twitter.com/JinaAI_) - follow and interact with us using hashtag `#JinaSearch`
- [Company](https://jina.ai) - know more about our company and how we are fully committed to open-source.
