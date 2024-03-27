## Hi! 👋 I am Margaret Foster, a quantitative researcher and data scientist. I am good at developing and implementing techniques to measure abstract or hard-to-capture problems. 

I am broadly trained, with most of my work focusing on interpretable strategies for analyzing text and event data. 

- 🔭 I’m currently working on developing the package for a bespoke Bayesian IRT Model that returns identifiable dimensions.
- 👯 I’m always looking for new, interesting, projects. Reach out via [LinkedIn](https://www.linkedin.com/in/margaretjfoster/) or email.
- ⚡ Fun fact: in a previous life, I was a qualitative threat hunter specializing in online extremist communities.
- 😄 Pronouns: she/her

## A guide to my current and previous work:

### Theoretically-grounded dimensionality reduction 

My current main line of research with a lab at Duke is on applying a novel Item Response Theory (IRT) model that produces interpretable underlying dimensions.
We are developing the code into an R package for distribution, 
We have applications to:

- Identifying latent "threat" dimensions for perception of threats to cultural, economic, health, religion, and society along with support for immigration and the European Union in the Februrary-March 2021 Eurobarometer survey (round 94.3).

### Measuring Geopolitical Risk Factors
I have a long-running research program on using machine learning and event data to estimate the behavior of actors who contribute to geopolitical threats. 
This is a tricky problem technically because data on internal processes is hard (or impossible!) to access. However, having estimates of change is important for improving risk evaluations because such actors decrease security and destabilize governance and trade.
Projects in that line of research include:

- [Subject to Change](https://github.com/margaretfoster/SubjectToChange/), which uses news reporting to estimate change years for civil war conflict actors. [You can check out the project](.slides/blob/main/Foster-TargetRWETalk_2024.pdf), via slides I prepared for a 2024 talk.

- [Growth Trap](https://github.com/margaretfoster/growthtrap_rep/) models the on-the-ground implications of internal organizational change in an opaque, high-impact, geopolitical actor. It models changes in target preferences in al-Qaeda in the Arabian Peninsula (AQAP) before and after the group expanded locally. The takeaway argument from the research is that while AQAP became stronger in the sense that they had/have access to more resources, they also became less of a global threat actor, likely due to the hyperlocal preferences of their new recruitment base.

### Custom Synthetic data

I have created synthetic data needed for custom applications.

- [Negotiations Sim](https://github.com/margaretfoster/wto_classification_sim/) This repository contains code to create synthetic text negotiation data with two competing frames of interest that may or may not overlap. I created it to help me develop and test methods to model and predict political outcomes in the data, including gridlock. The repository includes classification performance benchmarks at different levels of ground-truth labels for five popular machine learning algorithms (K-Nearest Neighbors, Naive Bayes, Random Forest, Ridge Regression, and Support Vector Machines). The tag levels (5%, 10%, or 25%) are intended to provide a guideline for researchers looking for a guideline for how much of this type of data to tag. Across all levels of ground truth, Random Forest performed best.

### Benchmarking the performance of quantitative methods applied to qualitative data 

I have designed and implemented custom code to benchmark the performance of quantitative methods applied to qualitative contexts. 

My work here focuses on techniques for (1) network and (2) unstructured text data.

- [Dominos](https://github.com/margaretfoster/Dominos), a model that simulates network-based recruitment and collapse of a community. The model tests the claim that users recruited into a community together tend to also leave together if any of them become unhappy. The simulation asks what network structures are most resilient to these disruptions. You can check out a design mockup of the project [here](./slides/blob/main/Dominos_Concept_Mockup.pdf) and [look at some of the results](./slides/blob/main/Dominos_Presentation_Dec92022.pdf) in the form of a presentation that I gave to a working group on Organizational Studies organized by Stanford's Center for Advanced Study in the Behavioral Science. The biggest takeaway is that "small world" type networks, where users have lots of local connections are the most stable when people start to leave. Conversely, communities that start with a few highly connected influencers are vulnerable to collapse... even if the influencers were part of the group before the new people came in!
 
- [Simulated Degradation](https://github.com/margaretfoster/SimulatedDegradation), takes an empirical network and a desired linear model and determines how robust the model results are to missing network data. The insights are twofold. First, looking at model instability helps understand which ties are important to the model results. These are the ties to focus on in the future. Second, this analysis helps verify that the model reflects the underlying network process.

### Presentations:

I have given workshops on applying data science concepts to real-world data and problems. One such workshop for the United Nations Department of Peacekeeping (UNDPO) [presented AI and NLP for peacekeeping data.](https://github.com/margaretfoster/slides/blob/main/AI%20and%20NLP%20for%20UN%20Data.pdf)

A deep dive of ML techniques used to profile the evolution of one such actor can be seen in [a 2022 presentation that I gave to the Sciences Po médialab.](https://github.com/margaretfoster/slides/blob/dcd71a8907c1e3f4a5fc4d2675334c47610c151a/Foster_SPML_Nov2022.pdf)

In 2024, I presented on [using NLP to estimate threat actor changes from recorded behavior.](https://github.com/margaretfoster/slides/blob/main/Foster-TargetRWETalk_2024.pdf) The benefit of this technique is that it is interpretable and can be done at scale.
